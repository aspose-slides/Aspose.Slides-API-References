---
title: AddVideoFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Video-Frame und fügt es am Ende der ShapeCollection hinzu.
type: docs
weight: 209
url: /de/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) Methode


Erstellt ein neues Video-Frame und fügt es am Ende der ShapeCollection hinzu.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | **float** | Die Breite des neuen Video-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Video-Frames in Punkten. |
| fname | [System::String](../../../system/string/) | Der Pfad oder Name der einzubettenden Videodatei. |

### Rückgabewert

Das neu erstellte [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) Methode


Erstellt ein neues Video-Frame und fügt es am Ende der ShapeCollection hinzu.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | **float** | Die Breite des neuen Video-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Video-Frames in Punkten. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Der [IVideo](../../ivideo/) zum Einbetten in das Video-Frame. |

### Rückgabewert

Das neu erstellte [IVideoFrame](../../ivideoframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoFrame](../../ivideoframe/)
* Klasse [String](../../../system/string/)
* Klasse [ShapeCollection](../)
* Klasse [IVideo](../../ivideo/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)