<span style="color: red"><em>DEPRECATED: As of March 23rd 2015 scriptcs is part of "core" Homebrew.</em></span>

# Homebrew-scriptcs

A [scriptcs](http://scriptcs.net/)
v0.13.3 formulae for the [Homebrew](http://brew.sh/)
package manager based on a [this gist](https://gist.github.com/akunzai/bbcac93646ca08bd8569)
by [akunzai](https://github.com/akunzai).

## Installation

[Mono](http://www.mono-project.com/) 3.0.0 (or newer) is a dependency
so this formula will install that.

Just `brew tap c0ntinuum/homebrew-scriptcs && brew install scriptcs` simples.

You could instead install directly via a URL:

```
brew install https://raw.github.com/c0ntinuum/homebrew-scriptcs/master/scriptcs.rb
```

## Updating & Upgrading

If you have previously installed scriptcs from this forumla simply:

```
brew update && brew upgrade mono scriptcs
```

## Testing

Run ```brew test scriptcs``` and you see:

```
Testing scriptcs
```

Run ```scriptcs```,
type ```Console.WriteLine("Hello, world!");```,
hit ```ENTER```
and you see:

```
Hello, world!
```
