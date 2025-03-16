# Sort Callback Method Demo

## What does Sort do?

```

The sort method allows an array's order to be sorted in different types of ways like, alphabetical, length, ascending, decending,
 ect. In doing so it modifies the origional array. Callbacks come into play with how it allows you to customize how things are
sorted. In the demo I'll show I will alphabetize a grocery list.

```

## Demo Code

```

const grocery = ['Bread', 'Coffee', 'Apples', 'Zebra Cakes']

const alphabetical = grocery.sort()
console.log('Alphabetical:', alphabetical)

Results:

Alphabetical: [ 'Apples', 'Bread', 'Coffee', 'Zebra Cakes' ]

```

## Let's comapre

```

Maps creates new arrays by making a copy of the original and altering the different parts of it to get the new outcome. While sort
 modifies the original array and sorts it however you coded it. So map returns a whole new array while sort returns a altered
 origional. There are no real similarities between the the 2 methods.   

```
