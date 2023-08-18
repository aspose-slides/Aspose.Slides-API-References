---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new OLE object to the end of a collection.
type: docs
weight: 66
url: /aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Adds a new OLE object to the end of a collection.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new OLE frame. |
| y | **float** | Y coordinate of a new OLE frame. |
| width | **float** | Width of a new OLE frame. |
| height | **float** | Height of a new OLE frame. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Embedded data info [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/). |

### Return Value

Created OLE object.

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method


Adds a new OLE object to the end of a collection.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new OLE frame. |
| y | **float** | Y coordinate of a new OLE frame. |
| width | **float** | Width of a new OLE frame. |
| height | **float** | Height of a new OLE frame. |
| className | [System::String](../../../system/string/) | Name of an OLE class. |
| path | [System::String](../../../system/string/) | path to the linked file. |

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