---
title: AsCast()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует тип источника в тип результата с помощью оператора приведения 'as'. Используется, когда требуется простое приведение, похожее на конструктор.
type: docs
weight: 2601
url: /ru/system/ascast/
---
## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется, когда требуется простой приведение, похожее на конструктор.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется, когда типы источника и результата одинаковы.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для обёрток исключений.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения. Возвращает `nullptr`, если преобразование недоступно.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для приведения объекта к исключению.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения. Возвращает `nullptr`, если преобразование недоступно.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется, когда и источник, и результат являются умными указателями.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения. Возвращает `nullptr`, если преобразование недоступно.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется, когда и источник, и результат являются умными указателями (с явным `SmartPtr<...>` в типе результата).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения. Возвращает `nullptr`, если преобразование недоступно.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для распаковки объекта в nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения. Возвращает пустой nullable, если преобразование недоступно.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Недопустимая распаковка в не-объектный тип.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Всегда возвращает `null`.

## System::AsCast(const Source\&) функция

Недопустимая распаковка в не-объектный тип.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Всегда возвращает `null`.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для упаковки nullable объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для упаковки обычного объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для упаковки обычного объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для распаковки строки.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для приведения `nullptr`.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения.

## System::AsCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью оператора приведения `as`. Используется для приведения между массивами.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### Возвращаемое значение

Результат приведения. Возвращает `nullptr`, если преобразование для любого элемента массива недоступно.

## См. также

* Определение типа [Exception](../exception/)
* Структура [CastResult](../castresult/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)