---
title: InsertClone()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 508
url: /pl/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metoda

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Zero-indeks, w którym ma zostać wstawiony sklonowany kształt. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu\\u2019s, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu\\u2019s, w punktach. |
| width | **float** | Szerokość ramki sklonowanego kształtu\\u2019s, w punktach. |
| height | **float** | Wysokość ramki sklonowanego kształtu\\u2019s, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metoda

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie. Nowy kształt zachowuje szerokość i wysokość *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Zero-indeks, w którym ma zostać wstawiony sklonowany kształt. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu\\u2019s, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu\\u2019s, w punktach. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metoda

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Zero-indeks, w którym ma zostać wstawiony sklonowany kształt. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) do sklonowania. |

### Wartość zwracana

Nowo utworzony [IShape](../../ishape/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)