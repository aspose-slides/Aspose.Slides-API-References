---
title: Span
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta una regione contigua di memoria arbitraria simile a std::span di C++20."
type: docs
weight: 1262
url: /it/system/span/
---
## Span classe

Rappresenta una regione contigua di memoria arbitraria simile a C++20's std::span.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span. Questa classe fornisce un modo type-safe per lavorare con sequenze contigue di oggetti. Può essere usata per avvolgere array, stack array o puntatori grezzi mantenendo il controllo dei limiti. Il [Span](./) non possiede la memoria a cui punta - è solo una vista sulla memoria esistente. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Clear](./clear/)() const | Cancella il contenuto dello span impostando tutti gli elementi al valore predefinito. |
| void [Fill](./fill/)(const T\&) const | Riempie lo span con il valore specificato. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Converte un array in un [Span](./). |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)