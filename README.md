
Experimental Production bundling with Rollup:

Prerequisites: Please use Node 8, the build is currently failing with Node 9.


Install dependencies:

```
bazel run @yarn//:yarn
```

Generate rollup bundle:

```
bazel build //src:bundle
```

Test using lite-server:

```
bazel run //src:web
```



