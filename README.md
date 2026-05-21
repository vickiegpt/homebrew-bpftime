# Homebrew Tap For bpftime

Install bpftime on macOS with Homebrew:

```sh
brew tap vickiegpt/bpftime
brew install bpftime
```

Or install without tapping first:

```sh
brew install vickiegpt/bpftime/bpftime
```

This formula currently targets macOS Apple Silicon and builds bpftime v0.2.0 in
non-Linux mode:

```sh
BPFTIME_BUILD_WITH_LIBBPF=OFF
BPFTIME_BUILD_KERNEL_BPF=OFF
BPFTIME_LLVM_JIT=OFF
BPFTIME_UBPF_JIT=ON
```

After installation:

```sh
bpftime --help
bpftimetool --help
```
