add_library(git_test1 "${CMAKE_CURRENT_LIST_DIR}/test1.cpp")

mediola_depend("git_test2" "e11d524b08e1c7a581955130f5103212418e2368")

target_include_directories(git_test1 PUBLIC "${CMAKE_CURRENT_LIST_DIR}")
