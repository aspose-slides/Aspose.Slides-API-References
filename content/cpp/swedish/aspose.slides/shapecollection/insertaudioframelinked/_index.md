---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny audio frame som länkas till en extern ljudfil och infogar den i shape collection på det angivna indexet.
type: docs
weight: 274
url: /sv/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metod

Skapar en ny audio frame som är länkat till en extern ljudfil och infogar den i shape collection på det angivna indexet.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där audio frame ska infogas. |
| x | **float** | x-koordinaten för den nya audio frame, i punkter. |
| y | **float** | y-koordinaten för den nya audio frame, i punkter. |
| width | **float** | Bredden på den nya audio frame, i punkter. |
| height | **float** | Höjden på den nya audio frame, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

### Returvärde

Den nyss skapade [IAudioFrame](../../iaudioframe/).

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudioFrame](../../iaudioframe/)
* Klass [String](../../../system/string/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)