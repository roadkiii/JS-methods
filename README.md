# List of JavaScript methods

* **Object.assign()**
  * Copies the values of all enumerable own properties from one or more source objects to a target object.
* **Object.create()**
  * Creates a new object with the specified prototype object and properties.
* **Object.defineProperty()**
  * Adds the named property described by a given descriptor to an object.
* **Object.defineProperties()**
  * Adds the named properties described by the given descriptors to an object.
* **Object.entries()**
  * Returns an array containing all of the [key, value] pairs of a given object's own enumerable string properties.
* **Object.freeze()**
  * Freezes an object: other code can't delete or change any properties.
* **Object.fromEntries()**
  * Returns a new object from an iterable of key-value pairs (reverses Object.entries).
* **Object.getOwnPropertyDescriptor()**
  * Returns a property descriptor for a named property on an object.
* **Object.getOwnPropertyDescriptors()**
  * Returns an object containing all own property descriptors for an object.
* **Object.getOwnPropertyNames()**
  * Returns an array containing the names of all of the given object's own enumerable and non-enumerable properties.
* **Object.getOwnPropertySymbols()**
  * Returns an array of all symbol properties found directly upon a given object.
* **Object.getPrototypeOf()**
  * Returns the prototype of the specified object.
* **Object.is()**
  * Compares if two values are the same value. Equates all NaN values (which differs from both Abstract Equality Comparison and Strict Equality Comparison).
* **Object.isExtensible()**
  * Determines if extending of an object is allowed.
* **Object.isFrozen()**
  * Determines if an object was frozen.
* **Object.isSealed()**
  * Determines if an object is sealed.
* **Object.keys()**
  * Returns an array containing the names of all of the given object's own enumerable string properties.
* **Object.preventExtensions()**
  * Prevents any extensions of an object.
* **Object.seal()**
  * Prevents other code from deleting properties of an object.
* **Object.setPrototypeOf()**
  * Sets the prototype (i.e., the internal [[Prototype]] property).
* **Object.values()**
  * Returns an array containing the values that correspond to all of a given object's own enumerable string properties.


## Array properties

* constructor 	Returns the function that created the Array object's prototype
* length 	Sets or returns the number of elements in an array
* prototype 	Allows you to add properties and methods to an Array object

## Array Methods
* concat()
  * Joins two or more arrays, and returns a copy of the joined arrays
* copyWithin()
  * Copies array elements within the array, to and from specified positions
* entries()
  * Returns a key/value pair Array Iteration Object
* every()
  * Checks if every element in an array pass a test
* fill()
  * Fill the elements in an array with a static value
* filter()
  * Creates a new array with every element in an array that pass a test
* find()
  * Returns the value of the first element in an array that pass a test
* findIndex()
  * Returns the index of the first element in an array that pass a test
* forEach()
  * Calls a function for each array element
* from()
  * Creates an array from an object
* includes()
  * Check if an array contains the specified element
* indexOf()
  * Search the array for an element and returns its position
* isArray()
  * Checks whether an object is an array
* join()
  * Joins all elements of an array into a string
* keys()
  * Returns a Array Iteration Object, containing the keys of the original array
* lastIndexOf()
  * Search the array for an element, starting at the end, and returns its position
* map()
  * Creates a new array with the result of calling a function for each array element
* pop()
  * Removes the last element of an array, and returns that element
* push()
  * Adds new elements to the end of an array, and returns the new length
* reduce()
  * Reduce the values of an array to a single value (going left-to-right)
* reduceRight()
  * Reduce the values of an array to a single value (going right-to-left)
* reverse()
  * Reverses the order of the elements in an array
* shift()
  * Removes the first element of an array, and returns that element
* slice()
  * Selects a part of an array, and returns the new array
* some()
  * Checks if any of the elements in an array pass a test
* sort()
  * Sorts the elements of an array
* splice()
  * Adds/Removes elements from an array
* toString()
  * Converts an array to a string, and returns the result
* unshift()
  * Adds new elements to the beginning of an array, and returns the new length
* valueOf()
  * Returns the primitive value of an array