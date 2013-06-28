# Ideas for a Compile-to-JavaScript language

  * `val` for constant values (maybe `const`?)
  * Type annotations with suffix `: T` notation (typesafety will be added later)

    E.g.: `val a: Number = 0.0;`
  * Function definition with `fn` keyword instead of `function` (maybe `def`?)
  * Anonymous function definition with `=>` notation

    E.g.: `(a, b) => { return a * b; }`
  * Error on using undefined variables
  * Error on defining variables without modifier
  * `==` will always become `===`
  * `if (a == ???) // ...` will translate to
    `if (typeof a === 'undefined') // ...`

But in general: **keep it simple!** JavaScript doesn't have to change that much
to become much simpler.
