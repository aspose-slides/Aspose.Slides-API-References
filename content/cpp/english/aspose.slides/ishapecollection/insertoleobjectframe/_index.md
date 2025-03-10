---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new OLE object and inserts it to a collection at the specified index.
type: docs
weight: 79
url: /aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Creates a new OLE object and inserts it to a collection at the specified index.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which OLE object should be inserted. |
| x | **float** | X coordinate of a new OLE frame. |
| y | **float** | Y coordinate of a new OLE frame. |
| width | **float** | Width of a new OLE frame. |
| height | **float** | Height of a new OLE frame. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Embedded data info [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/). |

### Return Value

Created OLE object.

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method


Creates a new OLE object and inserts it to a collection at the specified index.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which OLE object should be inserted. |
| x | **float** | X coordinate of a new OLE frame. |
| y | **float** | Y coordinate of a new OLE frame. |
| width | **float** | Width of a new OLE frame. |
| height | **float** | Height of a new OLE frame. |
| className | [System::String](../../../system/string/) | Name of an OLE class. |
| path | [System::String](../../../system/string/) | Path to the linked file. |

### Return Value

Created OLE object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)