# Swift libgit2
This is a Swift package manager module map for [libgit2](https://github.com/libgit2/libgit2). It assumes that you installed libgit2 with a prefix of `/usr/local`, which is the default for homebrew (`brew install libgit2`).

It's intended to just expose the c library to Swift.

To use add this to your `Package.swift` file dependencies: 
```swift
.Package(url: "https://github.com/therealbnut/swift-libgit2.git", majorVersion: 1)
```

You can then import it like this:
```swift
import Git2
```
