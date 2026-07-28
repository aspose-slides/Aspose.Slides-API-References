---
title: ExceptionWrapper
second_title: Odwołanie API Aspose.Slides dla C++
description: Szablon reprezentujący opakowanie wyjątków pochodzących od klasy Exception.
type: docs
weight: 833
url: /pl/system/exceptionwrapper/
---
## ExceptionWrapper klasa

Szablon reprezentujący opakowanie wyjątków pochodzących od klasy Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Tworzy instancję null klasy [ExceptionWrapper](./), która nie reprezentuje żadnego wyjątku. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Tworzy instancję klasy [ExceptionWrapper](./), która zawiera przekazany wskaźnik. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Konstruktor kopiujący. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Konstruktor przenoszący. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Konstruktor, który przekazuje parametry do konstruktorów klasy Exception i tworzy inteligentny wskaźnik trzymający nową instancję klasy Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Implicitny operator rzutowania na SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Umożliwia dostęp do członków obiektu Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Operator przypisania. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Operator przypisania przenoszącego. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Skrót do pobrania obiektu [System::TypeInfo](../typeinfo/) dla typu Exception. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Używany dla funkcji rzutujących. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)