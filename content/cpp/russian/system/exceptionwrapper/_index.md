---
title: ExceptionWrapper
second_title: Aspose.Slides для C++ справочника API
description: Шаблон, представляющий обёртку исключений, производных от класса Exception.
type: docs
weight: 833
url: /ru/system/exceptionwrapper/
---
## ExceptionWrapper класс

Шаблон, представляющий обёртку исключений, производных от класса Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Методы

| Метод | Описание |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Создаёт нулевой экземпляр класса [ExceptionWrapper](./), который не представляет никакое исключение. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Создаёт экземпляр класса [ExceptionWrapper](./), который содержит переданный указатель. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Конструктор копирования. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Конструктор перемещения. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Конструктор, который передаёт параметры конструкторам класса Exception и создаёт умный указатель, содержащий новый экземпляр класса Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Неявный оператор приведения к SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Позволяет получить доступ к членам объекта Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Оператор присваивания. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Оператор перемещения присваивания. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Сокращение для получения объекта [System::TypeInfo](../typeinfo/) для типа Exception. |
## Типы

| Тип | Описание |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Используется для функций приведения типов. |
## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)