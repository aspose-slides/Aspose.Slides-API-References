---
title: insertOleObjectFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 490
url: /php-java/shapecollection/insertoleobjectframe/
---

## insertOleObjectFrame(int index, float x, float y, float width, float height, [OleEmbeddedDataInfo](../../oleembeddeddatainfo) dataInfo)  method

 Creates a new OLE object and inserts it to a collection at the specified index.
 

 This example demonstrates inserting an OLE object at the second index:
 
```php
  $fileData = Files->readAllBytes(Paths->get("test.zip"));
  $dataInfo = new OleEmbeddedDataInfo($fileData, "zip");
  $oleObjectFrame = $slides->getShapes()->addOleObjectFrame(2, 150, 20, 50, $dataInfo);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which OLE object should be inserted. |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| dataInfo | [OleEmbeddedDataInfo](../../oleembeddeddatainfo) | Embedded data info IOleEmbeddedDataInfo. |

### Returns
[OleObjectFrame](../../oleobjectframe)


---


## insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)  method

 Creates a new OLE object and inserts it to a collection at the specified index.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which OLE object should be inserted. |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| className | String | Name of an OLE class. |
| path | String | Path to the linked file. |

### Returns
[OleObjectFrame](../../oleobjectframe)


---


