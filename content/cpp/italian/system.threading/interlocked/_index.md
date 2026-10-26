---
title: Interlocked
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce API per operazioni thread-safe. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 131
url: /it/system.threading/interlocked/
---
## Interlocked classe

Fornisce API per operazioni thread-safe. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Interlocked
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Incrementa il valore in modo atomico. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Incrementa il valore in modo atomico. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Confronta e scambia il valore sulla variabile: controlla se la variabile è uguale a un valore specifico e memorizza il nuovo valore solo se il valore memorizzato corrisponde a quello atteso. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Confronta e scambia il valore sulla variabile: controlla se la variabile è uguale a un valore specifico e memorizza il nuovo valore solo se il valore memorizzato corrisponde a quello atteso. Non implementato. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Confronta e scambia il valore sulla variabile: controlla se la variabile è uguale a un valore specifico e memorizza il nuovo valore solo se il valore memorizzato corrisponde a quello atteso. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Decrementa il valore in modo atomico. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Decrementa il valore in modo atomico. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Scambia il valore sulla variabile: memorizza il nuovo valore e restituisce il valore che la variabile aveva immediatamente prima della memorizzazione. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Scambia il valore sulla variabile: memorizza il nuovo valore e restituisce il valore che la variabile aveva immediatamente prima della memorizzazione. Non implementato. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Incrementa il valore in modo atomico tramite procedura di scambio-add. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Incrementa il valore in modo atomico tramite procedura di scambio-add. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Incrementa il valore in modo atomico. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Incrementa il valore in modo atomico. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Restituisce un valore a 64 bit, caricato come operazione atomica. |

## Vedi anche

* Spazio dei nomi [System::Threading](../)
* Libreria [Aspose.Slides](../../)