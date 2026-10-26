---
title: Interlocked
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt een API voor thread-veilige bewerkingen. Dit is een statisch type zonder instantie-services. U mag onder geen enkele omstandigheid instanties ervan maken.
type: docs
weight: 131
url: /nl/system.threading/interlocked/
---
## Interlocked klasse


Biedt een API voor thread-veilige bewerkingen. Dit is een statisch type zonder instantie-services. U mag onder geen enkele omstandigheid instanties ervan maken.

```cpp
class Interlocked
```

## Methoden

| Method | Description |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Verhoogt de waarde atomair. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Verhoogt de waarde atomair. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Vergelijkt en wisselt de waarde op de variabele: controleert of de variabele gelijk is aan een specifieke waarde en slaat de nieuwe waarde alleen op als de opgeslagen waarde overeenkomt met de verwachte. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Vergelijkt en wisselt de waarde op de variabele: controleert of de variabele gelijk is aan een specifieke waarde en slaat de nieuwe waarde alleen op als de opgeslagen waarde overeenkomt met de verwachte. Niet geïmplementeerd. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Vergelijkt en wisselt de waarde op de variabele: controleert of de variabele gelijk is aan een specifieke waarde en slaat de nieuwe waarde alleen op als de opgeslagen waarde overeenkomt met de verwachte. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Verlaagt de waarde atomair. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Verlaagt de waarde atomair. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Wisselt de waarde op de variabele: slaat de nieuwe waarde op en retourneert de waarde die de variabele onmiddellijk vóór het opslaan had. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Wisselt de waarde op de variabele: slaat de nieuwe waarde op en retourneert de waarde die de variabele onmiddellijk vóór het opslaan had. Niet geïmplementeerd. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Verhoogt de waarde atomair via een exchange-add-procedure. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Verhoogt de waarde atomair via een exchange-add-procedure. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Verhoogt de waarde atomair. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Verhoogt de waarde atomair. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Retourneert een 64-bit waarde, geladen als een atomare bewerking. |
## Zie ook

* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)