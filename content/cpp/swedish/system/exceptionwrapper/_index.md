---
title: ExceptionWrapper
second_title: Aspose.Slides för C++ API-referens
description: Mall som representerar en omslag för undantag som är avledda från Exception class.
type: docs
weight: 833
url: /sv/system/exceptionwrapper/
---
## ExceptionWrapper klass

Mall som representerar en omslag för undantag som är avledda från Exception class.

```cpp
template<typename T>class ExceptionWrapper
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Skapar en null-instans av [ExceptionWrapper](./) klass som inte representerar något undantag. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Skapar en instans av [ExceptionWrapper](./) klass som innehåller den överförda pekaren. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Kopieringskonstruktor. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Flyttkonstruktor. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Konstruktor som vidarebefordrar parametrar till Exception class-konstruktörerna och skapar en smart pekare som håller en ny Exception class-instans. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Implicit kastoperator till SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i Exception-objektet. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Tilldelningsoperator. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Flytt-tilldelningsoperator. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Genväg för att få [System::TypeInfo](../typeinfo/)-objektet för Exception-typen. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Används för kast-funktioner. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)