
# Manipulation des listes 

## Declaration de Variable
``` Javascript

``` var tab = ["alice", "bob", "charlie", ..., "Valeur?"] ``` 

## Acceder a lélément via lindex 

``` var idx = 0 
    tab [idx]; ``` 

## Slice > Selectioner une partie ciblée de la liste 

``` ``` 
## Ajouter au début de la liste 

``` tab.unshift(0) ```         ``` ``` 

## Ajouter a la fin de la liste 

``` tab.push(10) ```

## FunctionMap pour modifier tous les éléments de la liste 

``` var tab  = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]

var taber = tab.map(itemTab => {
    return itemTab * 1.5
})

console.log(taber)  ``` 

## FunctionReduce pour accumuler les éléments afin de former une valeur 

``` const initialValue = 0;

var numbers = [5, 10, 15, 25, 55];

var reducer = (accumulator, item) => {
  return accumulator + item;
};

var total = numbers.reduce(reducer, initialValue)

console.log(total)  ``` 

## FunctionSort pour remettre les valeurs dans lordre 

``` var tabsort = [0, 10, 30, 25, 20, 50, 70, 60, 55,].sort( (a,b) => {
    return a > b
})

console.log(tabsort) ``` 

## FunctionFilter pour filtrer les éléments de ta liste 


``` var tabfilter = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 0].filter( (item) => {
    return item % 2 === 0
})

console.log(tabfilter) ``` 

## FunctionFind pour trouver un élément dans ta liste 

 ``` var tabfind = ["Alice", "Bob", "Charlie", "David", "Eugène"];

var result = tabfind.find(user => user.startsWith("Charlie"));

console.log(result)  ``` 





