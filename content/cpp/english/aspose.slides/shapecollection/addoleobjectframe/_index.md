---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new OLE object to the end of a collection.
type: docs
weight: 183
url: /aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Adds a new OLE object to the end of a collection.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
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
## Remarks


The following examples shows how to adding OLE Object Frames to [Slides](../../) of PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Accesses the first slide
auto slide = pres->get_Slides()->idx_get(0);
// Loads an excel file to stream
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Creates a data object for embedding
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Adds an Ole Object Frame shape
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//Writes the PPTX file to disk
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```


## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method


Adds a new OLE object to the end of a collection.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new OLE frame. |
| y | **float** | Y coordinate of a new OLE frame. |
| width | **float** | Width of a new OLE frame. |
| height | **float** | Height of a new OLE frame. |
| className | [System::String](../../../system/string/) | Name of an OLE class. |
| path | [System::String](../../../system/string/) | Path to the linked file. |

### Return Value

Created OLE object.
## Remarks



The path is stored in the presentation as is. If a relative path is specified the corresponding file will be inaccessible when opening the presentation from a different directory.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)