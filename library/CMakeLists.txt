add_subdirectory(simulink-library)
install(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/matlab-wbc/ DESTINATION ${CMAKE_INSTALL_PREFIX}/mex)
