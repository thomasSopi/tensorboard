load("//tensorboard/defs:defs.bzl", "tf_ts_library")

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])

tf_ts_library(
    name = "tf_graph_node_search",
    srcs = ["tf-graph-node-search.ts"],
    strict_checks = False,
    visibility = ["//visibility:public"],
    deps = [
        "//tensorboard/components_polymer3/polymer:irons_and_papers",
        "//tensorboard/components_polymer3/polymer:legacy_element_mixin",
        "//tensorboard/components_polymer3/tf_dashboard_common",
        "//tensorboard/plugins/graph/polymer3/tf_graph_common",
        "@npm//@polymer/decorators",
        "@npm//@polymer/polymer",
        "@npm//@types/lodash",
        "@npm//lodash",
    ],
)
