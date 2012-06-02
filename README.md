letterate-haskell
=================


Consder the list homomoprhism of the alphabet to itself, under the transformations (toUpper, toLower).

Unfortunately, you'll want to zoom in to make the text larger (or draw it out by hand on paper).
I am assuming we're discussing only the properties of (monospaced, coding-type glyphs), for now.

But you can ignore that.

Just compare the properties of letters on the screen:


    A      a
    B      b
    C      c
    D      d
    E      e
    F      f
    G      g
    H      h
    I      i
    J      j
    K      k
    L      l
    M      m
    N      n
    O      o
    P      p
    Q      q
    R      r
    S      s
    T      t
    U      u
    V      v
    W      w
    X      x
    Y      y
    Z      z


What patterns do you see, when comparing left to right?

The easiest and most general one I see is that of self-similarity. I'll define this to mean, recognizable as
distinct after undergoing a scale transformation.

I'll define a scale trasnformation as imagining the character in a circle:

( C )

And then making the circle larger or smaller.


Several of these glyphs are not recognizable from each other under such a scale transformation:

    C      c

    M      m    (in some fonts)

    O      o
    P      p

    S      s

    U      u
    V      v
    W      w
    X      x

    Z      z


While these glyphs do not:

    A      a
    B      b
    D      d
    E      e
    F      f
    G      g
    H      h
    I      i
    J      j
    K      k
    L      l
    N      n
    Q      q
    R      r
    T      t
    Y      y
    


Now imagine just the procedure of putting the glyph inside a circle:

( C )

But what other transformations could we have?

You could rotate through an arbitrary angle, but if you stick to 90 degree angles, then the both X and x are self-inverse.

    X  x

Some of these letters are inverses of each other under up-down reflection:

    M m
    W w


Y is not on the list of scale-invariant things, but perhaps it should be. On the other hand, it is the up-down reflection of the lambda.

    Y  y 



# So what?

Ok, so we have some properties about some letters. How is this useful?

... (fill in as you guys read this crap)