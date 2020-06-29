**THIS IS MY SECOND TUTORIAL**
*Let's get started*
So, in the last tutorial, I had ***Python*** do a `print()`.
Now we are going to learn the `input()` function and what to avoid doing while typing the code in!

So **Python** understands `input` like this:
`input("Message goes here:")`
That runs like this:
Message goes here:*The person's typing goes here*
So the thing is, now the person has to type right into the colon!
We don't need that!
Let's fix it:
`input("Message goes here: ")`
The space ensures **Python** does a space before the person's typing.
But if anybody runs the code right now, they have to type in, but when they hit enter, the **program** stops.
*Oops!*
We have to go into `if statements` now!
If statements layout:
`if` *Whatever happens*`:`
    *The things when the thing happens go here*
The space is so **Python** understands when the code ends.
But we have to now put the `input()` into a variable, for example our modified code is now this:
`user = input("Message goes here: ")`
`if user == "ok":`
    `print("Well then!")`
So now, the `==` means equal to, like `+=` means plus the value, and `-=` minus the value.
The user now has to type ok, and then the computer says Well then!
If you want to add a responce, type `elif` instead of `if` for the second if, and for any other responce than you typed in any other `if`, then do an `else:` with nothing written of what happens.
So this is it for now, make sure you check more of my repositories, including tutorial ones!