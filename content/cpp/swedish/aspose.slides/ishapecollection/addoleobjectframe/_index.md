---
title: AddOleObjectFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen.
type: docs
weight: 66
url: /sv/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metod


Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Den inbäddade OLE-datainformationen ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Returvärde

Den nyss skapade [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) metod


Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| className | [System::String](../../../system/string/) | Klassnamnet på OLE-objektet. |
| path | [System::String](../../../system/string/) | Sökvägen till den länkade filen. |

### Returvärde

Den nyss skapade [IOleObjectFrame](../../ioleobjectframe/).

## Anmärkningar



Denna sökväg lagras exakt som den är i presentationen. Om en relativ sökväg anges kommer filen att vara oåtkomlig när presentationen öppnas från en annan katalog.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IOleObjectFrame](../../ioleobjectframe/)
* Klass [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klass [IShapeCollection](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)