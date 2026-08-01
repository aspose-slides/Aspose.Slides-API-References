---
title: ExceptionWrapper
second_title: Aspose.Slides voor C++ API-referentie
description: Sjabloon dat de wrapper van uitzonderingen weergeeft die zijn afgeleid van de Exception klasse.
type: docs
weight: 833
url: /nl/system/exceptionwrapper/
---
## ExceptionWrapper klasse

Sjabloon dat de wrapper van uitzonderingen weergeeft die zijn afgeleid van de Exception klasse.

```cpp
template<typename T>class ExceptionWrapper
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Construeert een null-instantie van [ExceptionWrapper](./) klasse die geen enkele uitzondering vertegenwoordigt. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Construeert een instantie van [ExceptionWrapper](./) klasse die de meegegeven pointer bevat. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Copy-constructor. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Move-constructor. |
|  explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Constructor die parameters doorgeeft aan de Exception klasse-constructors en een slimme pointer maakt die een nieuwe Exception klasse-instantie bevat. |
|  static void * [operator new](./operator_new/)(std::size_t) |  |
|  static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Impliciete cast-operator naar SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Staat toe leden van het Exception object te benaderen. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Toewijzingsoperator. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Move-toewijzingsoperator. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Snelkoppeling om het [System::TypeInfo](../typeinfo/) object voor het Exception type te krijgen. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Gebruikt voor cast-functies. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)