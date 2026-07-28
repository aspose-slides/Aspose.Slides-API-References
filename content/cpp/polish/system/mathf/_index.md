---
title: MathF
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Zawiera funkcje matematyczne dla wartości zmiennoprzecinkowych o pojedynczej precyzji. Jest to typ statyczny bez usług instancji. Nigdy nie powinno się tworzyć jego instancji w żaden sposób.
type: docs
weight: 1795
url: /pl/system/mathf/
---
## MathF struktura

Zawiera funkcje matematyczne dla wartości zmiennoprzecinkowych o pojedynczej precyzji. Jest to typ statyczny bez usług instancji. Nigdy nie powinno się tworzyć jego instancji w żaden sposób.

```cpp
class MathF
```

## Metody

| Metoda | Opis |
| --- | --- |
| static T [Abs](./abs/)(T) | Zwraca wartość bezwzględną podanej wartości. |
| static **float** [Acos](./acos/)(**float**) | Oblicza arcus cosinus podanej wartości. |
| static **float** [Asin](./asin/)(**float**) | Oblicza arcus sinus podanej wartości. |
| static **float** [Atan](./atan/)(**float**) | Oblicza arcus tangens podanej wartości. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Oblicza arcus tangens ilorazu podanych wartości. |
| static **float** [Ceiling](./ceiling/)(**float**) | Zwraca najmniejszą wartość całkowitą, która jest większa lub równa podanej wartości. |
| static **float** [Cos](./cos/)(**float**) | Oblicza cosinus podanej wartości. |
| static **float** [Cosh](./cosh/)(**float**) | Oblicza cosinus hiperboliczny podanej wartości. |
| static **float** [Exp](./exp/)(**float**) | Zwraca stałą e podniesioną do podanej potęgi. |
| static **float** [Floor](./floor/)(**float**) | Zwraca największą wartość całkowitą, która jest mniejsza lub równa podanej wartości. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Zwraca resztę z dzielenia jednej podanej liczby przez drugą podaną liczbę. |
| static **float** [Log](./log/)(**float**) | Zwraca logarytm naturalny podanej wartości. |
| static **float** [Log](./log/)(**float**, **float**) | Zwraca logarytm podanej wartości o podanej podstawie. |
| static **float** [Log10](./log10/)(**float**) | Zwraca logarytm dziesiętny podanej wartości. |
| static **float** [Pow](./pow/)(**float**, **float**) | Zwraca podaną wartość podniesioną do podanej potęgi. |
| static **float** [Round](./round/)(**float**) | Zaokrągla podaną wartość do najbliższej wartości całkowitej. |
| static **float** [Round](./round/)(**float**, int) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, gdy podana wartość jest tak samo odległa od dwóch najbliższych liczb. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. Parametr określa zachowanie funkcji, gdy podana wartość jest tak samo odległa od dwóch najbliższych liczb. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. Parametr określa zachowanie funkcji, gdy podana wartość jest tak samo odległa od dwóch najbliższych liczb. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Określa znak podanej liczby całkowitej ze znakiem. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Określa znak podanej wartości zmiennoprzecinkowej. |
| static **float** [Sin](./sin/)(**float**) | Oblicza sinus podanej wartości. |
| static **float** [Sinh](./sinh/)(**float**) | Oblicza sinus hiperboliczny podanej wartości. |
| static **float** [Sqrt](./sqrt/)(**float**) | Zwraca pierwiastek kwadratowy podanej wartości. |
| static **float** [Tan](./tan/)(**float**) | Oblicza tangens podanej wartości. |
| static **float** [Tanh](./tanh/)(**float**) | Oblicza tangens hiperboliczny podanej wartości. |
| static **float** [Truncate](./truncate/)(**float**) | Zwraca wartość zmiennoprzecinkową pojedynczej precyzji, której część całkowita jest równa części całkowitej podanej wartości, a wszystkie cyfry po przecinku zostają odrzucone. |

## Pola

| Pole | Opis |
| --- | --- |
| static [E](./e/) | Podstawa logarytmu naturalnego. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | Stała liczba Pi. |
| static [Tau](./tau/) | Wartość stałej Tau. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)