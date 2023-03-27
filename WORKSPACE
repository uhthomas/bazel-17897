load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_github_sourcegraph_sourcegraph",
    patch_args = ["-p1"],
    patches = ["//:com_github_sourcegraph_sourcegraph.patch"],
    sha256 = "f71a3712e6acffdcd54279ff96e5559e85ab54dd50922b6c86e5208889f90f75",
    strip_prefix = "sourcegraph-224c16693e2598348ce34f0822a1d71e859a163a",
    urls = ["https://github.com/sourcegraph/sourcegraph/archive/224c16693e2598348ce34f0822a1d71e859a163a.tar.gz"],
)
