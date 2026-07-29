---
title: AddAudioFrameLinked()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny ljudram som länkas till en extern ljudfil och lägger till den i slutet av formsamlingen.
type: docs
weight: 222
url: /sv/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) metod

Skapar en ny ljudram som länkas till en extern ljudfil och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya ljudramen, i punkter. |
| y | **float** | y-koordinaten för den nya ljudramen, i punkter. |
| width | **float** | Bredden på den nya ljudramen, i punkter. |
| height | **float** | Höjden på den nya ljudramen, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på den externa ljudfilen att länka. |

### Returvärde

Den nyss skapade [IAudioFrame](../../iaudioframe/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudioFrame](../../iaudioframe/)
* Klass [String](../../../system/string/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)