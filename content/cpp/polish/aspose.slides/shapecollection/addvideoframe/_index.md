---
title: AddVideoFrame()
second_title: Aspose.Slides dla C++ - Referencja API
description: Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 209
url: /pl/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) metoda


Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki wideo, w punktach. |
| y | **float** | Współrzędna y nowej ramki wideo, w punktach. |
| width | **float** | Szerokość nowej ramki wideo, w punktach. |
| height | **float** | Wysokość nowej ramki wideo, w punktach. |
| fname | [System::String](../../../system/string/) | Ścieżka lub nazwa pliku wideo do osadzenia. |

### Wartość zwracana

Nowo utworzony [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metoda


Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki wideo, w punktach. |
| y | **float** | Współrzędna y nowej ramki wideo, w punktach. |
| width | **float** | Szerokość nowej ramki wideo, w punktach. |
| height | **float** | Wysokość nowej ramki wideo, w punktach. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Obiekt [IVideo](../../ivideo/) do osadzenia w ramce wideo. |

### Wartość zwracana

Nowo utworzony [IVideoFrame](../../ivideoframe/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IVideoFrame](../../ivideoframe/)
* Klasa [String](../../../system/string/)
* Klasa [ShapeCollection](../)
* Klasa [IVideo](../../ivideo/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)