---
title: InsertVideoFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Position in die Shape-Collection ein.
type: docs
weight: 222
url: /de/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) Methode

Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Position in die Shape-Collection ein.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Video-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Video-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Video-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Video-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Video-Frames, in Punkten. |
| fname | [System::String](../../../system/string/) | Der Pfad oder Name der einzubettenden Videodatei. |

### Rückgabewert

Der neu erstellte [IVideoFrame](../../ivideoframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoFrame](../../ivideoframe/)
* Klasse [String](../../../system/string/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)