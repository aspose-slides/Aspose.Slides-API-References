---
title: InsertVideoFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Video-Frame und fügt es in die Shape-Collection an dem angegebenen Index ein.
type: docs
weight: 183
url: /de/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) Methode

Erstellt ein neues Video-Frame und fügt es in die Shape-Collection an der angegebenen Position ein.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das Video-Frame eingefügt wird. |
| x | **float** | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | **float** | Die Breite des neuen Video-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Video-Frames in Punkten. |
| fname | [System::String](../../../system/string/) | Der Pfad oder Name der einzubettenden Videodatei. |

### Rückgabewert

Das neu erstellte [IVideoFrame](../../ivideoframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoFrame](../../ivideoframe/)
* Klasse [String](../../../system/string/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)