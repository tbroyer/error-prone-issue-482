java_plugin(
    name = "test-annotation-processor",
    visibility = ["//visibility:public"],
    processor_class = "test.processor.TestProcessor",
    srcs = glob(["src/main/java/**/*.java"]),
    deps = [
      "@guava//jar",
      "//third_party/java/auto_service",
    ],
)

