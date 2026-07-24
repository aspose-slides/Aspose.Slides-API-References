---
title: AddVideoFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formensammlung hinzu.
type: docs
weight: 170
url: /de/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) Methode


Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formensammlung hinzu.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new video frame, in points. |
| y | **float** | The y-coordinate of the new video frame, in points. |
| width | **float** | The width of the new video frame, in points. |
| height | **float** | The height of the new video frame, in points. |
| fname | [System::String](../../../system/string/) | The path or name of the video file to embed. |

### Rückgabewert

The newly created [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) Methode


Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formensammlung hinzu.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | The x-coordinate of the new video frame, in points. |
| y | **float** | The y-coordinate of the new video frame, in points. |
| width | **float** | The width of the new video frame, in points. |
| height | **float** | The height of the new video frame, in points. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | The [IVideo](../../ivideo/) to embed in the video frame. |

### Rückgabewert

The newly created [IVideoFrame](../../ivideoframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoFrame](../../ivideoframe/)
* Klasse [String](../../../system/string/)
* Klasse [IShapeCollection](../)
* Klasse [IVideo](../../ivideo/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)