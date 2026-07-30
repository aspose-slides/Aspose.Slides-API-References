---
title: ExceptionWrapper
second_title: Riferimento API Aspose.Slides per C++
description: Modello che rappresenta un involucro per le eccezioni derivate dalla classe Exception.
type: docs
weight: 833
url: /it/system/exceptionwrapper/
---
## ExceptionWrapper classe


Modello che rappresenta un involucro per le eccezioni derivate dalla classe Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Costruisce un'istanza null di classe [ExceptionWrapper](./) che non rappresenta alcuna eccezione. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Costruisce un'istanza della classe [ExceptionWrapper](./) che contiene il puntatore passato. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Costruttore di copia. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Costruttore di spostamento. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Costruttore che inoltra i parametri ai costruttori della classe Exception e crea uno smart pointer che contiene una nuova istanza della classe Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Operatore di cast implicito a SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Consente di accedere ai membri dell'oggetto Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Operatore di assegnazione. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Operatore di assegnazione con spostamento. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Scorciatoia per ottenere l'oggetto [System::TypeInfo](../typeinfo/) per il tipo Exception. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Usato per le funzioni di casting. |
## Vedi anche

* namespace [System](../)
* Libreria [Aspose.Slides](../../)