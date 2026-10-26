---
title: Interlocked
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller API för trådsäkra operationer. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 131
url: /sv/system.threading/interlocked/
---
## Interlocked klass

Tillhandahåller API för trådsäkra operationer. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Interlocked
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Ökar värdet atomärt. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Ökar värdet atomärt. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Jämför-utbyter värdet på variabeln: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Jämför-utbyter värdet på variabeln: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. Ej implementerad. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Jämför-utbyter värdet på variabeln: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Minskar värdet atomärt. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Minskar värdet atomärt. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Byter värde på variabeln: lagrar det nya värdet och returnerar variabelns värde som den hade omedelbart innan lagringen. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Byter värde på variabeln: lagrar det nya värdet och returnerar variabelns värde som den hade omedelbart innan lagringen. Ej implementerad. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Ökar värdet atomärt via exchange-add-procedur. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Ökar värdet atomärt via exchange-add-procedur. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Ökar värdet atomärt. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Ökar värdet atomärt. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Returnerar ett 64-bitars värde, laddat som en atomär operation. |

## Se även

* Namnrymd [System::Threading](../)
* Bibliotek [Aspose.Slides](../../)