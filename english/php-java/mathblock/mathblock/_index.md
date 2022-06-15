---
title: MathBlock
type: docs
weight: 10
url: /php-java/mathblock/mathblock/
---

# MathBlock() constructor

 Initializes a new instance of the MathBlock class.
 
Example:
 
```php
  $mathBlock = new MathBlock();
```


# MathBlock(com.aspose.slides.IMathElement) constructor

 Creates a new mathematical block and puts specified element in it
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
```

##  Parameters

| name | description |
| --- | --- |
| mathElement | The mathematical element to put in the block |


# MathBlock(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement>) constructor

 Creates a new mathematical block and puts specified elements in it
 
Example:
 
```php
  $elems = new IMathElement[2];
  $mathBlock = new MathBlock($elems);
```

##  Parameters

| name | description |
| --- | --- |
| mathElements | Mathematical elements to put in the block |


