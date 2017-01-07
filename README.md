# Rust::from(lang)

If you've started to learn Rust and you've come from another language
you're strong in it can feel foreign or different. For some it's the
borrow checker, for others it's trying to apply OOP to things you
wouldn't in Rust, or maybe you make sure to check for `null`/`nil`/`undefined`
in other languages but `Option`/`Result` seem foreign in comparison.
That's where this project comes into play. If you look in the directory
of the language you're familiar with you'll find examples and common
patterns of the language you're used to and how to do it in a more Rust
like way.

## Contributing
Are you a more seasoned Rust Lang user? Help write some articles for
languages you're also passionate about! Noticed an error? Open up an
issue or a PR so it can get fixed! Felt like the explanation of
something could be better? Open up an issue and let us know how!

There's many ways you can contribute no matter how small a change or
issue. This is a project to help spread love and knowledge of Rust in
accordance with the community's 2017 goals of
[having a lower learning curve](https://github.com/aturon/rfcs/blob/roadmap-2017/text/0000-roadmap-2017.md#rust-should-have-a-lower-learning-curve).

### Opening an Issue
Before you open up an issue please check the issue tracker to make sure your
issue is not already in there. If it's a duplicate the correct issue
will be linked and your issue closed.

### Writing an Article
You can take a look at the [first article](./Haskell/error-handling.md)
written for an example of what the format is. In that article it was
Error Handling in Haskell vs Rust. Each article follows a basic format:

1. The problem is introduced
2. The language one is coming from and how it is normally done there is
   explained
3. The way one would do it in Rust
4. Comparing the strengths of how Rust does it
5. Comparing the weaknesses of how Rust does it
6. Possible stumbling blocks while transitioning from one language to
   Rust for this problem

It's a simple format but it provides a few useful things beyond
onboarding new users. It allows for comparisons between Rust and other
languages as well as being able to critically evaluate problems that
might occur for transitioning from one language to another. In the
example given above the mapping from Haskell to Rust is pretty much 1:1,
but other things like [Free
Monads](http://www.haskellforall.com/2012/06/you-could-have-invented-free-monads.html)
would take more work to show how to do it in Rust, or it might not be
something that should be done in Rust. This is where the stumbling
blocks section comes into play. If you're used to one way it might be
hard to switch to another and this addresses those concerns.

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
  <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" />
</a>
<br />
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
