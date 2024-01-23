# Single Cell: There Can Be Only One

## Project
This is a colab project to explore building a simple text-based application from scratch, based on a specification. It simulates a micro-ecosystem, where cells collide and the larger one consumes the smaller until only one remains. It's based on a superb tablet game called [Osmos](https://apps.apple.com/us/app/osmos-for-ipad/id379323382). Think about how to organize this code. You will probably have to research a bit to figure out how to build some parts.

## Specifications

Create an array of strings representing the names of all the contenders.

Using that array, populate an array of contenders, each an object with properties for name and size, which should start as 1.

Use a while loop to iterate as long as there's more than one contender. Each iteration, make two of the contenders battle
- select two different contenders at random from the array
- compare their sizes (you can choose how to break a tie)
- increase the size of the larger by 1, and remove the smaller from the array
- log some information about the battle and outcome.

Finally, log some information about the remaining winner.

## Next Steps

Do you have any other ideas to make this more interesting? Have fun with it!
