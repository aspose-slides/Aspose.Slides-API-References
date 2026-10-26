---
title: ToDecimal()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное логическое значение в эквивалентное десятичное число.
type: docs
weight: 235
url: /ru/system/convert/todecimal/
---
## Convert::ToDecimal(bool) метод

Преобразует указанное boolean значение в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) метод

Преобразует указанное 8-битное беззнаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) метод

Преобразует указанное 8-битное знаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) метод

Преобразует указанное 16-битное беззнаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) метод

Преобразует указанное 16-битное знаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) метод

Преобразует указанное 32-битное беззнаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) метод

Преобразует указанное 32-битное знаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) метод

Преобразует указанное 64-битное беззнаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) метод

Преобразует указанное 64-битное знаковое целое число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) метод

Преобразует указанное float число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) метод

Преобразует указанное double число в эквивалентное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) метод

Возвращает указанное десятичное число.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) метод

Преобразует указанную нулевую строку в эквивалентное [Decimal](../../decimal/) значение.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Возвращаемое значение

Ноль.

## Convert::ToDecimal(const char_t *) метод

Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное [Decimal](../../decimal/) значение.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

Значение [Decimal](../../decimal/) равное числу, представленному указанной C-строкой

## Convert::ToDecimal(const String\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное [Decimal](../../decimal/) значение.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

Значение [Decimal](../../decimal/) равное числу, представленному указанной строкой

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное [Decimal](../../decimal/) значение, используя предоставленную информацию о форматировании.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Значение [Decimal](../../decimal/) равное числу, представленному указанной строкой

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное [Decimal](../../decimal/) значение, используя указанные стили числа и информацию о форматировании.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовая комбинация значений перечисления NumberStyles, задающая допустимый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Значение [Decimal](../../decimal/) равное числу, представленному указанной строкой

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанное упакованное значение в эквивалентное [Decimal](../../decimal/) значение.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | SharedPtr к объекту, упаковывающему значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, используемый, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

Значение [Decimal](../../decimal/) эквивалентное указанному упакованному значению

## Смотрите также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [Decimal](../../decimal/)
* Класс [DateTime](../../datetime/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [Object](../../object/)
* Структура [Convert](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)