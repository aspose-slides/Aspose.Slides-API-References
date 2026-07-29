---
title: InsertOleObjectFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 196
url: /sv/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metod


Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där OLE-objektramen ska infogas. |
| x | **float** | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Den inbäddade OLE-datainformationen ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Returvärde

Den nyss skapade [IOleObjectFrame](../../ioleobjectframe/).

## Anmärkningar



Detta exempel visar hur man infogar ett OLE-objekt på det andra indexet: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metod


Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där OLE-objektramen ska infogas. |
| x | **float** | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| className | [System::String](../../../system/string/) | Klassnamnet för OLE-objektet. |
| path | [System::String](../../../system/string/) | Sökvägen till den länkade filen. |

### Returvärde

Den nyss skapade OLE-objektramen.

## Anmärkningar



Denna sökväg lagras exakt som den är i presentationen. Om en relativ sökväg anges kommer filen vara otillgänglig när presentationen öppnas från en annan katalog.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IOleObjectFrame](../../ioleobjectframe/)
* Klass [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klass [ShapeCollection](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)