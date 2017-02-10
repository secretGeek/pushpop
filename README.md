# pushpop

*mental stack manager*


You're working on one thing... another problem arises... or an interruption occurs... you need to push the new thing on top of your mental stack.

What do you do?

![everyday problems](image/Everyday+problems_690247_4723564.gif)


`pushpop` is a mental stack manager.

It lets you see the top of your mental stack.

![push pop](image/push_pop.png)

## Pop

When you've completed a task, click `pop`. (it makes a nice popping sound) and that task is gone.

The next item rises back to the top of the stack.

## Push

But wait... you are interrupted in your quest to complete the item on top of the stack.

What do you do? You enter the new item into the textbox, and `push` it. Now that item is on top.

![push pop pushed](image/push_pop_pushed.png)

## Peek

There's one more feature... `peek...`

![push pop](image/push_pop_peek.png)


Peek let's you inspect the entire mental stack. You can drag items around to reorder them. You can search for items (and can move the item you find to the top of the stack).

Finished peeking? Click `peeking...` to hide the stack away.

OK, OK, nerdy note... in proper '[stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type))' parlance, 'peek' is the operation that lets you see the item on top of the stack without popping it. Looking at the entire stack is called 'snooping' (well that's the slang term we used at university when i was kid...) But I'm using Peek here because I like the aliteration. The CLI would call it 'snoop' however.


## History

While peeking, you can also view previously completed items, if you click `history...`.


## Current status

As you can see from the balsamiq mockups above, this is just in the idea phase. It's based on [Next Action](http://www.timesnapper.com/NextAction/)


## cli

There could be commandline access.

    pushpop --peek                 # shows you what's on top
    pushpop --push "debug the sql" # puts a new item on top of your mental stack
    pushpop --pop                  # returns the top most item, but also removes it from the stack (and archives it?)
    pushpop --snoop                # shows all items currently in the stack, from top to bottom.
    pushpop --history              # shows all completed (i.e. previously popped items) including datetime of completion.
    pushpop --help                 # provides help with pushpop and life in general

## Implementation

Is left as exercise for the reader. I suggest [electron](http://electron.atom.io/).

If the stack was stored in the cloud &#2601;, then you could also have iOS/android version for stack operations while on the go.

## Last thing

I didn't mention Yak Shaving. Why didn't I mention yak shaving? Here's a yak in need of shave:

![Yak needing a shave](/image/yak.png)


Image from [wikimedia commons](https://commons.wikimedia.org/wiki/File:Yak_Yama.jpg)


---




