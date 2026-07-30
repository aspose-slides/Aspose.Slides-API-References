---
title: ExceptionWrapper
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Šablona, která představuje obal výjimek odvozených od třídy Exception.
type: docs
weight: 833
url: /cs/system/exceptionwrapper/
---
## ExceptionWrapper třída


Šablona, která představuje obal výjimek odvozených od třídy Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Vytvoří nulovou instanci třídy [ExceptionWrapper](./), která nepředstavuje žádnou výjimku. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Vytvoří instanci třídy [ExceptionWrapper](./), která obsahuje předaný ukazatel. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Kopírovací konstruktor. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Konstruktor přesunu. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Konstruktor, který předává parametry konstruktorům třídy Exception a vytváří inteligentní ukazatel, který drží novou instanci třídy Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Implicitní operátor přetypování na SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Umožňuje přístup k členům objektu Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Operátor přiřazení. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Operátor přiřazení přesunu. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Zkratka pro získání objektu [System::TypeInfo](../typeinfo/) pro typ Exception. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Použito pro funkce přetypování. |
## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)