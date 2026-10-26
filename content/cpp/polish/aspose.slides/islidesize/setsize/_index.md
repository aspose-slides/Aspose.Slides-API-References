---
title: SetSize()
second_title: Referencja API Aspose.Slides dla C++
description: "Ustawia rozmiar slajdu według typu i skaluje istniejącą zawartość. Przypisanie dowolnej wartości innej niż SlideSizeType::Custom dostosowuje ISlideSize::get_Size w zależności od wybranego typu, zachowując ISlideSize::get_Orientation."
type: docs
weight: 53
url: /pl/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metoda

Ustawia rozmiar slajdu według typu i skalowuje istniejącą zawartość. Przypisanie dowolnej wartości innej niż [SlideSizeType::Custom](../../slidesizetype/) dostosowuje [ISlideSize::get_Size](../get_size/) w zależności od wybranego typu, zachowując jednocześnie [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Predefiniowany rozmiar slajdu, który ma zostać zastosowany. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Tryb skalowania zawartości do użycia. |
## Uwagi

Przypisanie dowolnej wartości innej niż [SlideSizeType::Custom](../../slidesizetype/) dostosowuje [System::Drawing::Size](../../../system.drawing/size/) w zależności od wybranego typu, zachowując jednocześnie [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) metoda

Ustawia wymiary slajdu jawnie i skalowuje istniejącą zawartość. Resetuje wartość [ISlideSize::get_Type](../get_type/) do [SlideSizeType::Custom](../../slidesizetype/) i ustawia [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| width | **float** | Nowa szerokość slajdu w punktach. |
| height | **float** | Nowa wysokość slajdu w punktach. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Tryb skalowania zawartości do użycia. |
## Uwagi

Resetuje właściwość [ISlideSize::get_Type](../get_type/) do [SlideSizeType::Custom](../../slidesizetype/) i ustawia [Orientation](../../orientation/). 

## Zobacz także

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Klasa [ISlideSize](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)