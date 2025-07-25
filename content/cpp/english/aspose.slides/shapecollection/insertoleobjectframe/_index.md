---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new OLE object frame and inserts it into the shape collection at the specified index.
type: docs
weight: 196
url: /aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Creates a new OLE object frame and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the OLE object frame. |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | The embedded OLE data information ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Return Value

The newly created [IOleObjectFrame](../../ioleobjectframe/).
## Remarks



This example demonstrates inserting an OLE object at the second index: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method


Creates a new OLE object frame and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the OLE object frame. |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| className | [System::String](../../../system/string/) | The class name of the OLE object. |
| path | [System::String](../../../system/string/) | The path to the linked file. |

### Return Value

The newly created OLE object frame.
## Remarks



This path is stored verbatim in the presentation. If a relative path is specified, the file will be inaccessible when opening the presentation from a different directory.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)