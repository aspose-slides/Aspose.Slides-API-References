---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Shape-Collection ein.
type: docs
weight: 235
url: /de/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) Methode


Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Shape-Collection ein.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames in Punkten. |
| fname | [System::String](../../../system/string/) | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

### Rückgabewert

Der neu erstellte [IAudioFrame](../../iaudioframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [String](../../../system/string/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)