---
title: AddAudioFrameLinked()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny ljudram som länkas till en extern ljudfil och lägger till den i slutet av shape collection.
type: docs
weight: 261
url: /sv/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) metod

Skapar en ny ljudram som länkas till en extern ljudfil och lägger till den i slutet av shape collection.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | Y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

### Returvärde

Den nyss skapade [IAudioFrame](../../iaudioframe/).

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)