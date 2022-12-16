---
title: getAudios
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/presentation/getaudios/
---

## getAudios()  method

 Returns the collection of all embedded audio files in the presentation.
 Read-only  IAudioCollection.
 

 The following examples shows how to add a hyperlink to an audio file.
 
```php
  $pres = new Presentation();
  try {
    $audio = $pres->getAudios()->addAudio(Files->readAllBytes(Paths->get("audio.mp3")));
    $audioFrame = $pres->getSlides()->get_Item(0)->getShapes()->addAudioFrameEmbedded(10, 10, 100, 100, $audio);
    $audioFrame->setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
    $audioFrame->getHyperlinkClick()->setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
    $pres->save("pres-out.pptx", SaveFormat.Pptx);
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[AudioCollection](../../audiocollection)


---


