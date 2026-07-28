---
title: ReadOnlySpan
second_title: Dokumentacja API Aspose.Slides dla C++
description: Przekierowanie do użycia w klasie Span.
type: docs
weight: 1210
url: /pl/system/readonlyspan/
---
## ReadOnlySpan klasa

Forward do użycia w klasie [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie. Ta klasa zapewnia typowo-bezpieczny sposób pracy z ciągłymi sekwencjami obiektów w trybie tylko do odczytu. Może być używana do opakowywania tablic, tablic stosowych lub surowych wskaźników przy zachowaniu sprawdzania granic. [ReadOnlySpan](./) nie posiada pamięci, na którą wskazuje – jest to jedynie widok istniejącej pamięci. |

## Metody

| Metoda | Opis |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Tworzy zakres tylko do odczytu z zwykłego zakresu. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Konwertuje tablicę na [ReadOnlySpan](./). |

## Uwagi

Reprezentuje tylko do odczytu spójny obszar dowolnej pamięci.

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)