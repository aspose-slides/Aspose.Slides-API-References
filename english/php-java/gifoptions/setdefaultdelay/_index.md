---
title: setDefaultDelay
type: docs
weight: 60
url: /php-java/gifoptions/setdefaultdelay/
---

# setDefaultDelay(int) method

 Gets or sets default delay time [ms]. This value will be used if ( ISlideShowTransition#getAdvanceAfterTime/ ISlideShowTransition#setAdvanceAfterTime(long)) is not set.
 The default value is 1000.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $gifOptions = new GifOptions();
    $gifOptions->setDefaultDelay(2000);
    $pres->save("pres.gif", SaveFormat.Gif, $gifOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
ISlideShowTransition#setAdvanceAfterTime(long)

