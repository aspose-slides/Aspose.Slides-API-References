---
title: InsertOleObjectFrame
second_title: Aspose.Sildes for .NET API Reference
description: Creates a new OLE object frame and inserts it into the shape collection at the specified index.
type: docs
weight: 350
url: /aspose.slides/shapecollection/insertoleobjectframe/
---

## InsertOleObjectFrame(int, float, float, float, float, IOleEmbeddedDataInfo) {#insertoleobjectframe}

Creates a new OLE object frame and inserts it into the shape collection at the specified index.

```csharp
public IOleObjectFrame InsertOleObjectFrame(int index, float x, float y, float width, float height, 
    IOleEmbeddedDataInfo dataInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The zero-based index at which to insert the OLE object frame. |
| x | Single | The x-coordinate of the new OLE frame, in points. |
| y | Single | The y-coordinate of the new OLE frame, in points. |
| width | Single | The width of the new OLE frame, in points. |
| height | Single | The height of the new OLE frame, in points. |
| dataInfo | IOleEmbeddedDataInfo | The embedded OLE data information ([`IOleEmbeddedDataInfo`](../../ioleembeddeddatainfo)). |

### Return Value

The newly created [`IOleObjectFrame`](../../ioleobjectframe).

### Examples

This example demonstrates inserting an OLE object at the second index:

```csharp
[C#]
byte[] fileData = File.ReadAllBytes("test.zip");
IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
IOleObjectFrame oleObjectFrame = slidees.Shapes.AddOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
```

### See Also

* interface [IOleObjectFrame](../../ioleobjectframe)
* interface [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertOleObjectFrame(int, float, float, float, float, string, string) {#insertoleobjectframe_1}

Creates a new OLE object frame and inserts it into the shape collection at the specified index.

```csharp
public IOleObjectFrame InsertOleObjectFrame(int index, float x, float y, float width, float height, 
    string className, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The zero-based index at which to insert the OLE object frame. |
| x | Single | The x-coordinate of the new OLE frame, in points. |
| y | Single | The y-coordinate of the new OLE frame, in points. |
| width | Single | The width of the new OLE frame, in points. |
| height | Single | The height of the new OLE frame, in points. |
| className | String | The class name of the OLE object. |
| path | String | The path to the linked file. |

### Return Value

The newly created OLE object frame.

### See Also

* interface [IOleObjectFrame](../../ioleobjectframe)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
