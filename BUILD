cc_binary(
    name = 'byacc',
    visibility = [
        '//visibility:public',
    ],
    srcs = [
        'src/closure.c',
        'src/error.c',
        'src/lalr.c',
        'src/lr0.c',
        'src/main.c',
        'src/mkpar.c',
        'src/output.c',
        'src/reader.c',
        'src/skeleton.c',
        'src/symtab.c',
        'src/verbose.c',
        'src/warshall.c',
        'src/defs.h',
    ],
    copts = [
        # Suppress known warnings.
        '-Wno-compare-distinct-pointer-types',
        '-Wno-dangling-else',
        '-Wno-format-extra-args',
        '-Wno-implicit-function-declaration',
        '-Wno-incompatible-pointer-types',
        '-Wno-sometimes-uninitialized',
        '-Wno-unused-variable',
    ],
)
