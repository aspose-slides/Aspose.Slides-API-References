---
title: setTransitionFps
type: docs
weight: 90
url: /php-java/gifoptions/settransitionfps/
---

# setTransitionFps(int) method

 Gets or sets transition FPS [frames/sec]
 The default value is 25.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $gifOptions = new GifOptions();
    $gifOptions->setTransitionFps(60);
    $pres->save("pres.gif", SaveFormat.Gif, $gifOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


