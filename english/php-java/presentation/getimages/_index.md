---
title: getImages
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 200
url: /php-java/presentation/getimages/
---

## getImages()  method

 Returns the collection of all images in the presentation.
 Read-only  IImageCollection.
 

 The following examples shows how to add image as BLOB in PowerPoint Presentation.
 
```php
  // create a new presentation which will contain this image
  $pres = new Presentation();
  try {
    // supposed we have the large image file we want to include into the presentation
    $fip = new FileInputStream("large_image.jpg");
    try {
      // let's add the image to the presentation - we choose KeepLocked behavior, because we not
      // have an intent to access the "largeImage.png" file.
      $img = $pres->getImages()->addImage($fip, LoadingStreamBehavior.KeepLocked);
      $pres->getSlides()->get_Item(0)->getShapes()->addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, $img);
      // save the presentation. Despite that the output presentation will be
      // large, the memory consumption will be low the whole lifetime of the pres object
      $pres->save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
    } finally {
      $fip->close();
    }
  } catch (JavaException $e) {
  } finally {
    $pres->dispose();
  }
```

### Returns
[ImageCollection](../../imagecollection)


---


