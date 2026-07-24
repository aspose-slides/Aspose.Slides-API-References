---
title: ExceptionWrapper
second_title: Aspose.Slides für C++ API-Referenz
description: Vorlage, die einen Wrapper für Ausnahmen darstellt, die von der Klasse Exception abgeleitet sind.
type: docs
weight: 833
url: /de/system/exceptionwrapper/
---
## ExceptionWrapper Klasse

Template, die einen Wrapper für Ausnahmen darstellt, die von der Klasse Exception abgeleitet sind.

```cpp
template<typename T>class ExceptionWrapper
```

## Methoden

| Method | Description |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Konstruiert eine Null-Instanz der Klasse [ExceptionWrapper](./), die keine Ausnahme darstellt. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Konstruiert eine Instanz der Klasse [ExceptionWrapper](./), die den übergebenen Zeiger enthält. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Kopierkonstruktor. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Verschiebekonstruktor. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Konstruktor, der Parameter an die Konstruktoren der Klasse Exception weiterleitet und einen Smart-Pointer erzeugt, der eine neue Instanz der Klasse Exception hält. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Impliziter Cast-Operator zu SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des Exception-Objekts. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Zuweisungsoperator. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Verschiebezuweisungsoperator. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Abkürzung, um das [System::TypeInfo](../typeinfo/)-Objekt für den Exception-Typ zu erhalten. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Wird für Cast-Funktionen verwendet. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)