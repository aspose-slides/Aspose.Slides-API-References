---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny ljudram som länkas till en extern ljudfil och infogar den i shape-samlingen på det angivna indexet.
type: docs
weight: 235
url: /sv/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metod


Skapar en ny ljudram kopplad till en extern ljudfil och infogar den i shape-samlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade index där ljudramen ska infogas. |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

### Returvärde

Det nyss skapade [IAudioFrame](../../iaudioframe/).

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IAudioFrame](../../iaudioframe/)
* Klass [String](../../../system/string/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)