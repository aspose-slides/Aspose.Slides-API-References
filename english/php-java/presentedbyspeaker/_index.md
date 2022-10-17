---
title: PresentedBySpeaker
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/presentedbyspeaker/
---

## PresentedBySpeaker class

 Presented by a speaker (full screen)
 

 
```php
  $pres = new Presentation();
  try {
    $pres->getSlideShowSettings()->setSlideShowType(new PresentedBySpeaker());
    $pres->save("pres.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| Name | Description |
| --- | --- |
| [PresentedBySpeaker](presentedbyspeaker)() | Initializes a new instance of the PresentedBySpeaker class. |
