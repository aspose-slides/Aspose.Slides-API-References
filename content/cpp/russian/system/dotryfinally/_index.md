---
title: DoTryFinally()
second_title: Aspose.Slides для C++ справочник API
description: Единственная функция, имитирующая поведение оператора try[-catch]-finally в C#. При трансляции оператора try[-catch]-finally из C# с включённой опцией переводчика finally_statement_as_lambda, оператор переводится в вызов этого метода.
type: docs
weight: 2406
url: /ru/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) функция

Единственная функция, имитирующая поведение оператора try[-catch]-finally в C#. При трансляции оператора try[-catch]-finally из C# с включённой опцией переводчика finally_statement_as_lambda, оператор переводится в вызов этого метода.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объект-функции, реализующей часть try[-catch] имитируемого оператора try[-catch]-finally |
| F | Тип объект-функции, реализующей часть finally имитируемого оператора try[-catch]-finally |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryBlock | T\&& | Объект-функция, тело которой содержит реализацию части try[-catch] имитируемого оператора try[-catch]-finally |
| finallyBlock | F\&& | Объект-функция, тело которой содержит реализацию части finally имитируемого оператора try[-catch]-finally |

## System::DoTryFinally(T\&&, F\&&) функция

Единственная функция, имитирующая поведение оператора try[-catch]-finally в C#. При трансляции оператора try[-catch]-finally из C# с включённой опцией переводчика finally_statement_as_lambda, оператор переводится в вызов этого метода. Эта перегрузка обрабатывает случай, когда возвращаемое значение объект-функции, реализующей часть try[-catch] имитируемого оператора, имеет тип bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объект-функции, реализующей часть try[-catch] имитируемого оператора try[-catch]-finally |
| F | Тип объект-функции, реализующей часть finally имитируемого оператора try[-catch]-finally |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryBlock | T\&& | Объект-функция, тело которой содержит реализацию части try[-catch] имитируемого оператора try[-catch]-finally |
| finallyBlock | F\&& | Объект-функция, тело которой содержит реализацию части finally имитируемого оператора try[-catch]-finally |

## System::DoTryFinally(T\&&, F\&&) функция

Единственная функция, имитирующая поведение оператора try[-catch]-finally в C#. При трансляции оператора try[-catch]-finally из C# с включённой опцией переводчика finally_statement_as_lambda, оператор переводится в вызов этого метода. Эта перегрузка обрабатывает случай, когда возвращаемое значение объект-функции, реализующей часть try[-catch] имитируемого оператора, имеет тип bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объект-функции, реализующей часть try[-catch] имитируемого оператора try[-catch]-finally |
| F | Тип объект-функции, реализующей часть finally имитируемого оператора try[-catch]-finally |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryBlock | T\&& | Объект-функция, тело которой содержит реализацию части try[-catch] имитируемого оператора try[-catch]-finally |
| finallyBlock | F\&& | Объект-функция, тело которой содержит реализацию части finally имитируемого оператора try[-catch]-finally |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)