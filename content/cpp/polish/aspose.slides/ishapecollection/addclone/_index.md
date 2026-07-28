---
title: AddClone()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 495
url: /pl/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metoda


Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Kształt do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |
| width | **float** | Szerokość ramki sklonowanego kształtu, w punktach. |
| height | **float** | Wysokość ramki sklonowanego kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metoda


Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) metoda


Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)