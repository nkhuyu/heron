package(default_visibility = ["//visibility:public"])

load("/tools/rules/pex_rules", "pex_binary")

pex_binary(
    name = "http-server",
    srcs = [
        "main.py"
    ],
    main = "main.py",
    reqs = [
        "tornado==4.0.2",
    ],
)
