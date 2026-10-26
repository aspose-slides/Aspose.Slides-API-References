---
title: SetSize()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Ustawia rozmiar slajdu według typu i skaluje istniejącą zawartość.
type: docs
weight: 53
url: /pl/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metoda

Ustawia rozmiar slajdu według typu i skaluje istniejącą zawartość.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Wstępnie zdefiniowany rozmiar slajdu do zastosowania. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Tryb skalowania zawartości do użycia. |

## Uwagi

Przypisanie dowolnej wartości innej niż [SlideSizeType::Custom](../../slidesizetype/) dostosowuje [SlideSize::get_Size](../get_size/) na podstawie wybranego typu, zachowując [SlideSize::get_Orientation](../get_orientation/).

## SlideSize::SetSize(float, float, SlideSizeScaleType) metoda

Ustawia wymiary slajdu jawnie i skaluje istniejącą zawartość.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| width | **float** | Nowa szerokość slajdu, w punktach. |
| height | **float** | Nowa wysokość slajdu, w punktach. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Tryb skalowania zawartości do użycia. |

## Uwagi

To resetuje właściwość [SlideSize::get_Type](../get_type/) do [SlideSizeType::Custom](../../slidesizetype/) i ustawia [Orientation](../../orientation/).

## Zobacz także

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [SlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)