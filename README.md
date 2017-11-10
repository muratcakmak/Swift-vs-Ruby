# Swift-vs-Ruby

## Comments
Both languages support one-line and multi-line comments
```
# Ruby 

=begin
  multi-line 
  code comment
=end


// Swift 

/*
  multi-line
  code comment
*/
```


## Constant and Variable declaration
Ruby doesn't have constant. Swift does.

```
# Ruby

legal_age = 18

// Swift 

let legalAge = 18 //This is a constant

var currentAge = 27 //This is variable
```

## String Interpolation

```
# Ruby

name = "Oguzhan"
puts "Hello, #{name}."

// Swift

let name = "Oguzhan"
print("Hello, \(name)")
```

## Type Inference
Ruby is a dynamic type language. A variable can store anything: integers, strings, floats, objects.
Swift is a type safe language. Compiler yells at your code, if you try to reassing an integer to string variable. However, Swift has a type inference. 
```
# Ruby 
name = "Oguzhan"
name = 89.00

// Swift 
var name = "Oguzhan"
name = 89.00 // Compiler Error!

```

## Further Readings
* [An introduction to Swift for Ruby Developers](http://www.aidanf.net/posts/an-introduction-to-swift-for-ruby-developers)
* [Swift for Rubyists](https://academy.realm.io/posts/swift-for-rubyists/)
* [5 Reasons Why Rubyist Will Love Swift](https://littlelines.com/blog/2014/06/11/why-rubyist-will-love-swift)

