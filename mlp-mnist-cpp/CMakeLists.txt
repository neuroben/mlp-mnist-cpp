# CMakeList.txt : CMake project for mlp-mnist-cpp, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (mlp-mnist-cpp "mlp-mnist-cpp.cpp" "mlp-mnist-cpp.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET mlp-mnist-cpp PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
