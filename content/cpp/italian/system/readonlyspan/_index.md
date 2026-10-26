---
title: ReadOnlySpan
second_title: Riferimento API Aspose.Slides per C++
description: Da utilizzare all'interno della classe Span.
type: docs
weight: 1210
url: /it/system/readonlyspan/
---
## ReadOnlySpan classe

Da utilizzare all'interno della classe [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span. Questa classe fornisce un modo tipo-sicuro per lavorare con sequenze contigue di oggetti in modalità di sola lettura. Può essere usata per avvolgere array, array sullo stack o puntatori grezzi mantenendo il controllo dei limiti. Il [ReadOnlySpan](./) non possiede la memoria a cui punta – è solo una vista sulla memoria esistente. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Costruisce uno span di sola lettura da uno span regolare. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Converte un array in un [ReadOnlySpan](./). |

## Osservazioni

Rappresenta una regione contigua di sola lettura di memoria arbitraria.

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)