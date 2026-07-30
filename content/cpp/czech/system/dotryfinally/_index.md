---
title: DoTryFinally()
second_title: Aspose.Slides pro C++ API Reference
description: Jedná se o jedinou funkci, která emuluje chování příkazu try[-catch]-finally jazyka C#. Během překladu příkazu try[-catch]-finally jazyka C# s volbou překladače finally_statement_as_lambda nastavenou na true je tento příkaz přeložen na volání této metody.
type: docs
weight: 2445
url: /cs/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) funkce

Jedná se o jedinou funkci, která emuluje chování příkazu try[-catch]-finally jazyka C#. Během překladu příkazu try[-catch]-finally jazyka C# s volbou překladače finally_statement_as_lambda nastavenou na true je tento příkaz přeložen na volání této metody.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ funkčního objektu, který implementuje část try[-catch] příkazu try[-catch]-finally, který je emulován |
| F | Typ funkčního objektu, který implementuje část finally příkazu try[-catch]-finally, který je emulován |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tryBlock | T\&& | Funkční objekt, jehož tělo obsahuje implementaci části try[-catch] příkazu try[-catch]-finally, který je emulován |
| finallyBlock | F\&& | Funkční objekt, jehož tělo obsahuje implementaci části finally příkazu try[-catch]-finally, který je emulován |

## System::DoTryFinally(T\&&, F\&&) funkce

Jedná se o jedinou funkci, která emuluje chování příkazu try[-catch]-finally jazyka C#. Během překladu příkazu try[-catch]-finally jazyka C# s volbou překladače finally_statement_as_lambda nastavenou na true je tento příkaz přeložen na volání této metody. Tato přetížení řeší případ, kdy návratová hodnota funkčního objektu implementujícího část try[-catch] příkazu try[-catch]-finally je typu bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ funkčního objektu, který implementuje část try[-catch] příkazu try[-catch]-finally, který je emulován |
| F | Typ funkčního objektu, který implementuje část finally příkazu try[-catch]-finally, který je emulován |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tryBlock | T\&& | Funkční objekt, jehož tělo obsahuje implementaci části try[-catch] příkazu try[-catch]-finally, který je emulován |
| finallyBlock | F\&& | Funkční objekt, jehož tělo obsahuje implementaci části finally příkazu try[-catch]-finally, který je emulován |

## System::DoTryFinally(T\&&, F\&&) funkce

Jedná se o jedinou funkci, která emuluje chování příkazu try[-catch]-finally jazyka C#. Během překladu příkazu try[-catch]-finally jazyka C# s volbou překladače finally_statement_as_lambda nastavenou na true je tento příkaz přeložen na volání této metody. Tato přetížení řeší případ, kdy návratová hodnota funkčního objektu implementujícího část try[-catch] příkazu try[-catch]-finally je typu bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ funkčního objektu, který implementuje část try[-catch] příkazu try[-catch]-finally, který je emulován |
| F | Typ funkčního objektu, který implementuje část finally příkazu try[-catch]-finally, který je emulován |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tryBlock | T\&& | Funkční objekt, jehož tělo obsahuje implementaci části try[-catch] příkazu try[-catch]-finally, který je emulován |
| finallyBlock | F\&& | Funkční objekt, jehož tělo obsahuje implementaci části finally příkazu try[-catch]-finally, který je emulován |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)