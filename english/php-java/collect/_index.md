---
title: Collect
type: docs
weight: 0
url: /php-java/collect/
---

# Collect class

 Represents a group of methods intended to collect model objects of different types from  Presentation.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    for ($shape : Collect->shapes($pres)) {
      // ... change shape formatting or other properties
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| name | description |
| --- | --- |
| [Collect](/slides/php-java/collect/collect/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [shapes](/slides/php-java/collect/shapes/)(Presentation) | IGenericEnumerable | Collects all instances of Shape in the Presentation. |
