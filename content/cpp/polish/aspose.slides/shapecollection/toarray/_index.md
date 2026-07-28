---
title: ToArray()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy i zwraca tablicę zawierającą wszystkie kształty.
type: docs
weight: 326
url: /pl/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() metoda


Tworzy i zwraca tablicę zawierającą wszystkie kształty.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### Wartość zwracana

Tablica obiektów [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) metoda


Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks pierwszego kształtu do zwrócenia. |
| count | **int32_t** | Liczba kształtów do zwrócenia. |

### Wartość zwracana

Tablica obiektów [IShape](../../ishape/).

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../ishape/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)