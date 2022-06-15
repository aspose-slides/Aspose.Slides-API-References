---
title: setEmbeddedData
type: docs
weight: 130
url: /php-java/oleobjectframe/setembeddeddata/
---

# setEmbeddedData(com.aspose.slides.IOleEmbeddedDataInfo) method

 Sets information about OLE embedded data.
 

 
```php
  $pres = new Presentation("SomePresentation.pptx");
  try {
    $oof = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    if ($oof != null) {
      $newData = new OleEmbeddedDataInfo(Files->readAllBytes(Paths->get("Picture.png")), "png");
      $oof->setEmbeddedData($newData);
    }
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| embeddedData | Embedded data IOleEmbeddedDataInfo This method changes the properties of the object to reflect the new data and sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |

##  Exception
ArgumentNullException When embeddedData parameter is null.


