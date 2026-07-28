---
title: Span
second_title: Aspose.Slides dla C++ dokumentacja API
description: "Reprezentuje spójny obszar dowolnej pamięci, podobny do std::span z C++20."
type: docs
weight: 1262
url: /pl/system/span/
---
## Klasa Span

Reprezentuje spójny region dowolnej pamięci podobny do C++20's std::span.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w span. Ta klasa zapewnia bezpieczny typowo sposób pracy z ciągłymi sekwencjami obiektów. Może być używana do opakowywania tablic, tablic stosowych lub surowych wskaźników przy zachowaniu sprawdzania granic. [Span](./) nie posiada pamięci, na którą wskazuje – to tylko widok istniejącej pamięci. |

## Metody

| Metoda | Opis |
| --- | --- |
| void [Clear](./clear/)() const | Czyści zawartość span, ustawiając wszystkie elementy na wartość domyślną. |
| void [Fill](./fill/)(const T\&) const | Wypełnia span podaną wartością. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Konwertuje tablicę na [Span](./). |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)