---
title: addOleObjectFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 170
url: /php-java/shapecollection/addoleobjectframe/
---

## addOleObjectFrame(float x, float y, float width, float height, [OleEmbeddedDataInfo](../../OleEmbeddedDataInfo) dataInfo)  method

 Adds a new OLE object to the end of a collection.
 

 This example demonstrates adding an OLE object to the end of a collection:
 
```php
  $fileData = Files->readAllBytes(Paths->get("test.zip"));
  $dataInfo = new EmbeddedDataInfo($fileData, "zip");
  $oleObjectFrame = $slidees->getShapes()->addOleObjectFrame(150, 20, 50, 50, $dataInfo);
```

### Parameters

| Name | Description |
| --- | --- |
| x | X coordinate of a new OLE frame. |
| y | Y coordinate of a new OLE frame. |
| width | Width of a new OLE frame. |
| height | Height of a new OLE frame. |
| dataInfo | Embedded data info IOleEmbeddedDataInfo. |

### Returns
Created OLE object.


---


## addOleObjectFrame(float x, float y, float width, float height, String className, String path)  method

 Adds a new OLE object to the end of a collection.
 

### Parameters

| Name | Description |
| --- | --- |
| x | X coordinate of a new OLE frame. |
| y | Y coordinate of a new OLE frame. |
| width | Width of a new OLE frame. |
| height | Height of a new OLE frame. |
| className | Name of an OLE class. |
| path | Path to the linked file.The path is stored in the presentation as is. If a relative path is specified the corresponding file will be inaccessible when opening the presentation from a different directory. |

### Returns
Created OLE object.


---


