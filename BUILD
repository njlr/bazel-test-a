cc_library(
  name = "a",
  includes = [
    "include",
  ],
  hdrs = glob([
    "include/*.hpp",
  ]),
  srcs = glob([
    "include/*.hpp",
    "src/*.cpp",
  ]),
  visibility = [
    "//visibility:public",
  ],
)

cc_binary(
  name = "app",
  srcs = [
    "main.cpp",
  ],
  deps = [
    ":a",
  ],
)
