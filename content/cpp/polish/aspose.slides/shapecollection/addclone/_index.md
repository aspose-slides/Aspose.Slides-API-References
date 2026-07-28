---
title: AddClone()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 547
url: /pl/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metoda

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Kształt do sklonowania. |
| x | **float** | Współrzędna x ramki nowego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki nowego kształtu, w punktach. |
| width | **float** | Szerokość ramki nowego kształtu, w punktach. |
| height | **float** | Wysokość ramki nowego kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metoda

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość *sourceShape*.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Kształt do sklonowania. |
| x | **float** | Współrzędna x ramki nowego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki nowego kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) metoda

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)