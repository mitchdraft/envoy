load("@envoy_api//bazel:api_build_system.bzl", "api_proto_library")

licenses(["notice"])  # Apache 2

api_proto_library(
    name = "health_check_event",
    srcs = ["health_check_event.proto"],
    visibility = [
        "//visibility:public",
    ],
    deps = [
        "//envoy/api/v2/core:address",
        "//envoy/api/v2/core:base",
    ],
)
