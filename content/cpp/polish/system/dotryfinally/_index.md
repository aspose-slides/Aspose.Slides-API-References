---
title: DoTryFinally()
second_title: Aspose.Slides dla C++ Referencja API
description: Jedna funkcja, która emuluje zachowanie instrukcji try[-catch]-finally języka C#. Podczas tłumaczenia instrukcji try[-catch]-finally języka C# z opcją translatora finally_statement_as_lambda ustawioną na true, instrukcja zostaje przetłumaczona na wywołanie tej metody.
type: docs
weight: 2445
url: /pl/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) funkcja


Ta pojedyncza funkcja emuluje zachowanie instrukcji try[-catch]-finally języka C#. Podczas tłumaczenia instrukcji try[-catch]-finally języka C# z opcją translatora finally_statement_as_lambda ustawioną na true, instrukcja jest tłumaczona na wywołanie tej metody.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu funkcyjnego, który implementuje część try[-catch] instrukcji try[-catch]-finally będącej emulowaną |
| F | Typ obiektu funkcyjnego, który implementuje część finally instrukcji try[-catch]-finally będącej emulowaną |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tryBlock | T\&& | Obiekt funkcyjny, którego ciało zawiera implementację części try[-catch] instrukcji try[-catch]-finally będącej emulowaną |
| finallyBlock | F\&& | Obiekt funkcyjny, którego ciało zawiera implementację części finally instrukcji try[-catch]-finally będącej emulowaną |

## System::DoTryFinally(T\&&, F\&&) funkcja


Ta pojedyncza funkcja emuluje zachowanie instrukcji try[-catch]-finally języka C#. Podczas tłumaczenia instrukcji try[-catch]-finally języka C# z opcją translatora finally_statement_as_lambda ustawioną na true, instrukcja jest tłumaczona na wywołanie tej metody. Ta przeciążona wersja obsługuje przypadek, w którym wartość zwracana obiektu funkcyjnego implementującego część try[-catch] instrukcji try[-catch]-finally jest typu bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu funkcyjnego, który implementuje część try[-catch] instrukcji try[-catch]-finally będącej emulowaną |
| F | Typ obiektu funkcyjnego, który implementuje część finally instrukcji try[-catch]-finally będącej emulowaną |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tryBlock | T\&& | Obiekt funkcyjny, którego ciało zawiera implementację części try[-catch] instrukcji try[-catch]-finally będącej emulowaną |
| finallyBlock | F\&& | Obiekt funkcyjny, którego ciało zawiera implementację części finally instrukcji try[-catch]-finally będącej emulowaną |

## System::DoTryFinally(T\&&, F\&&) funkcja


Ta pojedyncza funkcja emuluje zachowanie instrukcji try[-catch]-finally języka C#. Podczas tłumaczenia instrukcji try[-catch]-finally języka C# z opcją translatora finally_statement_as_lambda ustawioną na true, instrukcja jest tłumaczona na wywołanie tej metody. Ta przeciążona wersja obsługuje przypadek, w którym wartość zwracana obiektu funkcyjnego implementującego część try[-catch] instrukcji try[-catch]-finally jest typu bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu funkcyjnego, który implementuje część try[-catch] instrukcji try[-catch]-finally będącej emulowaną |
| F | Typ obiektu funkcyjnego, który implementuje część finally instrukcji try[-catch]-finally będącej emulowaną |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tryBlock | T\&& | Obiekt funkcyjny, którego ciało zawiera implementację części try[-catch] instrukcji try[-catch]-finally będącej emulowaną |
| finallyBlock | F\&& | Obiekt funkcyjny, którego ciało zawiera implementację części finally instrukcji try[-catch]-finally będącej emulowaną |

## Zobacz także

* Namespace [System](../)
* Library [Aspose.Slides](../../)