---
title: InsertOleObjectFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 79
url: /sv/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metod


Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där OLE-objekt-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Den inbäddade OLE-datainformation ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Returvärde

Den nyss skapade [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metod


Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där OLE-objekt-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| className | [System::String](../../../system/string/) | Klassnamnet för OLE-objektet. |
| path | [System::String](../../../system/string/) | Sökvägen till den länkade filen. |

### Returvärde

Den nyss skapade [IOleObjectFrame](../../ioleobjectframe/).

## Anmärkningar



Denna sökväg lagras oförändrad i presentationen. Om en relativ sökväg anges kommer filen vara oåtkomlig när presentationen öppnas från en annan katalog.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)