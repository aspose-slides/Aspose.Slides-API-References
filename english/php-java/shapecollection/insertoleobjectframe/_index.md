---
title: insertOleObjectFrame
type: docs
weight: 490
url: /php-java/shapecollection/insertoleobjectframe/
---

# insertOleObjectFrame(int, float, float, float, float, com.aspose.slides.IOleEmbeddedDataInfo) method

 Creates a new OLE object and inserts it to a collection at the specified index.
 

 This example demonstrates inserting an OLE object at the second index:
 
```php
  $fileData = Files->readAllBytes(Paths->get("test.zip"));
  $dataInfo = new OleDataInfo($fileData, "zip");
  $oleObjectFrame = $slidees->getShapes()->addOleObjectFrame(2, 150, 20, 50, 50, $dataInfo);
```

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index at which OLE object should be inserted. |
| x | X coordinate of a new OLE frame. |
| y | Y coordinate of a new OLE frame. |
| width | Width of a new OLE frame. |
| height | Height of a new OLE frame. |
| dataInfo | Embedded data info IOleEmbeddedDataInfo. |

##  Returns
Created OLE object.


# insertOleObjectFrame(int, float, float, float, float, java.lang.String, java.lang.String) method

 Creates a new OLE object and inserts it to a collection at the specified index.
 

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index at which OLE object should be inserted. |
| x | X coordinate of a new OLE frame. |
| y | Y coordinate of a new OLE frame. |
| width | Width of a new OLE frame. |
| height | Height of a new OLE frame. |
| className | Name of an OLE class. |
| path | Path to the linked file. |

##  Returns
Created OLE object.

