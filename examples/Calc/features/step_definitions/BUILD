load("//gherkin:defs.bzl", "cc_gherkin_steps")

cc_gherkin_steps(
    name = "calculator_steps",
    srcs = [
        "CalculatorSteps.cpp",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//examples/Calc/src:calculator",
        "@cucumber_cpp//src:cucumber_main",
        "@gtest",
    ],
)
