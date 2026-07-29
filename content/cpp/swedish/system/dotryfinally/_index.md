---
title: DoTryFinally()
second_title: Aspose.Slides för C++ API-referens
description: Den enkla funktionen som efterliknar beteendet hos C#'s try[-catch]-finally-sats. Vid översättning av C#'s try[-catch]-finally-sats med översättarens alternativ finally_statement_as_lambda satt till true översätts satsen till ett anrop av denna metod.
type: docs
weight: 2445
url: /sv/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) funktion

Den enkla funktionen som efterliknar beteendet hos C#'s try[-catch]-finally-sats. Vid översättning av C#'s try[-catch]-finally-sats med översättarens alternativ finally_statement_as_lambda satt till true översätts satsen till ett anrop av denna metod.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som implementerar try[-catch]-delen av den try[-catch]-finally-sats som efterliknas |
| F | Typen av funktionsobjektet som implementerar finally-delen av den try[-catch]-finally-sats som efterliknas |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryBlock | T\&& | Funktionsobjektet vars kropp innehåller implementationen av try[-catch]-delen av den try[-catch]-finally-sats som efterliknas |
| finallyBlock | F\&& | Funktionsobjektet vars kropp innehåller implementationen av finally-delen av den try[-catch]-finally-sats som efterliknas |

## System::DoTryFinally(T\&&, F\&&) funktion

Den enkla funktionen som efterliknar beteendet hos C#'s try[-catch]-finally-sats. Vid översättning av C#'s try[-catch]-finally-sats med översättarens alternativ finally_statement_as_lambda satt till true översätts satsen till ett anrop av denna metod. Denna överlagring hanterar fallet där returvärdet för funktionsobjektet som implementerar try[-catch]-delen av try[-catch]-finally-satsen är bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som implementerar try[-catch]-delen av den try[-catch]-finally-sats som efterliknas |
| F | Typen av funktionsobjektet som implementerar finally-delen av den try[-catch]-finally-sats som efterliknas |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryBlock | T\&& | Funktionsobjektet vars kropp innehåller implementationen av try[-catch]-delen av den try[-catch]-finally-sats som efterliknas |
| finallyBlock | F\&& | Funktionsobjektet vars kropp innehåller implementationen av finally-delen av den try[-catch]-finally-sats som efterliknas |

## System::DoTryFinally(T\&&, F\&&) funktion

Den enkla funktionen som efterliknar beteendet hos C#'s try[-catch]-finally-sats. Vid översättning av C#'s try[-catch]-finally-sats med översättarens alternativ finally_statement_as_lambda satt till true översätts satsen till ett anrop av denna metod. Denna överlagring hanterar fallet där returvärdet för funktionsobjektet som implementerar try[-catch]-delen av try[-catch]-finally-satsen är bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som implementerar try[-catch]-delen av den try[-catch]-finally-sats som efterliknas |
| F | Typen av funktionsobjektet som implementerar finally-delen av den try[-catch]-finally-sats som efterliknas |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryBlock | T\&& | Funktionsobjektet vars kropp innehåller implementationen av try[-catch]-delen av den try[-catch]-finally-sats som efterliknas |
| finallyBlock | F\&& | Funktionsobjektet vars kropp innehåller implementationen av finally-delen av den try[-catch]-finally-sats som efterliknas |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)