# You Don't Know JS: Async & Performance
# Chapter 4: Generators

In Chapter 2, we identified two key drawbacks to expressing async flow control with callbacks:

* Callback-based async doesn't fit how our brain plans out steps of a task.
* Callbacks aren't trustable or composable because of *inversion of control*.

In Chapter 3, we detailed how Promises uninvert the *inversion of control* of callbacks, restoring trustability/composability.

Now we turn our attention to expressing async flow control in a sequential, synchronous-looking fashion. The "magic" that makes it possible is ES6 **generators**.

