---
title: getTransitionFps
type: docs
weight: 50
url: /php-java/gifoptions/gettransitionfps/
---

# getTransitionFps() method

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


