load("@rules_qt//:qt.bzl", "qt_cc_binary", "qt_cc_library")

qt_cc_library(
    name = "main_window",
    srcs = ["mainwindow.cpp"],
    hdrs = ["mainwindow.h", "ui_mainwindow.h"],
    deps = [
        "@rules_qt//:qt_core",
        "@rules_qt//:qt_gui",
        "@rules_qt//:qt_widgets",
    ],
)

qt_cc_binary(
    name = "Task2",
    srcs = ["main.cpp"],
    deps = [
        ":main_window",
        "@rules_qt//:qt_widgets",
    ],
)

