---
title: Collect
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/collect/
---

## Collect class

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

| Name | Description |
| --- | --- |
| [Collect](collect)() |  |

## Methods

| Name | Description |
| --- | --- |
| [shapes](shapes)([Presentation](../presentation)) | Collects all instances of Shape in the Presentation. |
