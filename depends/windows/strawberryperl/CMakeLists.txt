cmake_minimum_required(VERSION 3.5)

project(strawberryperl VERSION 5.30.1.1)

file(WRITE ${CMAKE_CURRENT_BINARY_DIR}/StrawberryPerlConfig.cmake "set(STRAWBERRYPERL_PATH ${CMAKE_CURRENT_SOURCE_DIR}/perl/bin)\n")
install(FILES ${CMAKE_CURRENT_BINARY_DIR}/StrawberryPerlConfig.cmake DESTINATION ${CMAKE_INSTALL_PREFIX})
