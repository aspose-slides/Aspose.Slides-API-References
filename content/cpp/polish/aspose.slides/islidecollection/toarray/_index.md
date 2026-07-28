---
title: ToArray()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy i zwraca tablicę ze wszystkimi slajdami.
type: docs
weight: 92
url: /pl/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() metoda

Tworzy i zwraca tablicę ze wszystkimi slajdami.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### Wartość zwracana

Tablica [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) metoda

Tworzy i zwraca tablicę ze slajdami z określonego zakresu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks pierwszego slajdu do dodania. |
| count | **int32_t** | Liczba slajdów do dodania. |

### Wartość zwracana

Tablica [ISlide](../../islide/)

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [ISlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)