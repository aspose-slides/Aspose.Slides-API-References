---
title: GetDateTimeFormats()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает массив строк, где каждый элемент представляет строковое представление текущего объекта, отформатированного с помощью одного из стандартных спецификаторов формата даты и времени.
type: docs
weight: 547
url: /ru/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const метод

Возвращает массив строк, где каждый элемент представляет строковое представление текущего объекта, отформатированного с помощью одного из стандартных спецификаторов формата даты и времени.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const метод

Возвращает массив строк, где каждый элемент представляет строковое представление текущего объекта, отформатированного с указанным стандартным спецификатором формата даты и времени.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | char_t | Стандартный спецификатор формата даты и времени. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const метод

Возвращает массив строк, где каждый элемент представляет строковое представление текущего объекта, отформатированного с помощью одного из стандартных спецификаторов формата даты и времени и указанного поставщика форматов.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик форматов. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const метод

Возвращает массив строк, где каждый элемент представляет строковое представление текущего объекта, отформатированного с указанным стандартным спецификатором формата даты и времени и поставщиком форматов.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | char_t | Стандартный спецификатор формата даты и времени. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик форматов. |

## См. также

* Тип [ArrayPtr](../../arrayptr/)
* Тип [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [DateTime](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)