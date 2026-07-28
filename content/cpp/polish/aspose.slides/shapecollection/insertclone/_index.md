---
title: InsertClone()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 560
url: /pl/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metoda

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić sklonowany kształt. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |
| width | **float** | Szerokość ramki sklonowanego kształtu, w punktach. |
| height | **float** | Wysokość ramki sklonowanego kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metoda

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie. Nowy kształt zachowuje szerokość i wysokość *sourceShape*.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić sklonowany kształt. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metoda

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić sklonowany kształt. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## Zobacz również

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)