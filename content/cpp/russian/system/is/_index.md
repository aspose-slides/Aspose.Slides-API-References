---
title: Is()
second_title: Aspose.Slides для справочника API C++
description: Реализует перевод шаблона объявления 'is'.
type: docs
weight: 2276
url: /ru/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) функция

Реализует перевод шаблона объявления 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| PatternT | тип для проверки. |
| ExpressionT | тип левого выражения. |
| ResultT | тип результирующего выражения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const ExpressionT\& | выражение, которое будет проверено. |
| result | ResultT\& | переменная, которой будет присвоен проверенный тип. |

### Возвращаемое значение

true если проверка типа выполнена успешно, false в противном случае.

## System::Is(const ExpressionT\&, const ConstantT\&) функция

Реализует перевод шаблона констант 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ExpressionT | тип левого выражения. |
| ConstantT | тип константного выражения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const ExpressionT\& | выражение, которое будет проверено. |
| constant | const ConstantT\& | выражение, которое будет сравниваться с левым. |

### Возвращаемое значение

true если проверка типа выполнена успешно, false в противном случае.

## System::Is(const E\&, const A\&) функция

Функция сопоставления верхнего уровня. Применяет шаблон к значению.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| A | Тип шаблона (должен наследоваться от Details::Pattern). |
| E | Тип значения для сопоставления. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| e | const E\& | значение для сопоставления. |
| a | const A\& | шаблон для применения. |

### Возвращаемое значение

true если проверка типа выполнена успешно, false в противном случае.

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)