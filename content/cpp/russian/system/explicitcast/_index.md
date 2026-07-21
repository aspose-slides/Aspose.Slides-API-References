---
title: ExplicitCast()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует тип источника в тип результата с помощью явного приведения. Используется, когда типы источника и результата одинаковы.
type: docs
weight: 2588
url: /ru/system/explicitcast/
---
## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется, когда типы источника и результата совпадают.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется, когда требуется простое приведение, похожее на конструктор.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для обёрток исключений.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для приведения объекта к исключению.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется, когда и источник, и результат являются умными указателями (без явного SmartPtr<...> в типе результата).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(Source) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется при преобразовании необработанного указателя в умный указатель.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | Source | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется, когда и источник, и результат являются умными указателями (с явным SmartPtr<...> в типе результата).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для развёртывания объекта в nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для упаковывания nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для развёртывания nullable-объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для упаковки enum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для копирования типовых значений в кучу, когда тип значения должен ссылаться как умный указатель (в дженериках, ограниченных типом интерфейса, но специализируемых структурой, реализующей этот интерфейс).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для получения интерфейсов из типовых значений.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для обычной упаковки.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для упаковки [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для развёртывания интерфейсов.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для обычного развёртывания.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для приведения к nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## System::ExplicitCast(const Source\&) функция

Преобразует тип источника в тип результата с помощью явного приведения. Используется для приведения между массивами.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### Возвращаемое значение

The cast result.

## См. также

* Typedef [Exception](../exception/)
* Класс [SmartPtr](../smartptr/)
* Класс [BoxedValueBase](../boxedvaluebase/)
* Структура [CastResult](../castresult/)
* Пространство имён [System](../)
* Library [Aspose.Slides](../../)