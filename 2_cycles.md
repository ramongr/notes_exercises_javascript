# Loops and iteration

##### How it works and why it's important

Any structure in programming that's more complex than numbers or characters will use some kind of iteration. This means that understand how to traverse more complex structures is vital to programming and to any functioning application.

### Arrays - Simple and multidimensional

A simple array is a collection of items, a multidimensional array is a collection of a collection of items. A simple array is usually just called _an array_ and a multidimensional array is usually called _an array of arrays_. Both those names serve as an indication of what they should store and what they represent.
An array stores linear items, such as a list of strings or a list of integers. It serves to represent a collection of elements related to each other but have no property other than themselves.
When dealing with _array of arrays_ you're probably talking about more complex structures, and more likely that would apply in real world scenario. Whichever one you're using they have the same behaviour as you'll see in the examples below:

Example 1: A simple array can be accessed through the use of an index. An index is a way to point at a specific element inside the array. The first index is 0 and the last index is the length of the array subtracting 1.

```javascript
  var array = [1, 2, 3];

  // array[0] -> 1
  // array[1] -> 2
  // array[2] -> 3
```

Example 2: Any array can be looped until


### Iteration

Let's say you're managing stock and you want to have items name and it's stock. Considering an array to deal with that information is the correct way to go. But how? One option is to have something like this:

```javascript
  var stockItems = ['Portal 2', 'CS: Go', 'Amnesia'],
      stockItemValues = [10, 5, 3];
```

Each variable tells you only one thing, the item list or the amount of items in stock. Their relation is merely positional, this means that you could understand that we have 10 Portal 2 games in stock but it's not easy to read.

Another option is to
### How it works - Logic
