---
title: getDefaultDelay
type: docs
weight: 20
url: /php-java/gifoptions/getdefaultdelay/
---

# getDefaultDelay() method

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


