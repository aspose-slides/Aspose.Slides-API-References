---
title: insert
type: docs
weight: 160
url: /php-java/mathblock/insert/
---

# insert(int, com.aspose.slides.IMathElement) method

 Inserts a MathElement into the collection at the specified index.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->add($plusElement);
  $mathBlock->insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index at which MathElement should be inserted. |
| item | The MathElement to insert. |


