---
title: ToChar()
second_title: Справочник API Aspose.Slides для C++
description: Преобразование не поддерживается. Всегда генерирует InvalidCastException.
type: docs
weight: 118
url: /ru/system/convert/tochar/
---
## Convert::ToChar(bool) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) метод


Преобразует указанный беззнаковый 8-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) метод


Преобразует указанный знаковый 8-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) метод


Преобразует указанный беззнаковый 16-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) метод


Преобразует указанный знаковый 16-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) метод


Преобразует указанный беззнаковый 32-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) метод


Преобразует указанный знаковый 32-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) метод


Преобразует указанный беззнаковый 64-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) метод


Преобразует указанный знаковый 64-битный целочисленный тип в эквивалентный символ Unicode.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) метод


Возвращает указанный символ Unicode.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) метод


Преобразует первый и единственный символ указанной C-строки в значение типa char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования; ожидается, что строка содержит ровно 1 символ. |

### Возвращаемое значение

Первый и единственный символ указанной C-строки, если она состоит ровно из 1 символа, иначе - 0

## Convert::ToChar(const String\&) метод


Преобразует первый и единственный символ указанной строки в значение типa char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования; ожидается, что строка содержит ровно 1 символ. |

### Возвращаемое значение

Первый и единственный символ указанной строки, если она состоит ровно из 1 символа, иначе - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует первый и единственный символ указанной строки в значение типa char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования; ожидается, что строка содержит ровно 1 символ. |

### Возвращаемое значение

Первый и единственный символ указанной строки, если она состоит ровно из 1 символа, иначе - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанное упакованное значение в эквивалентный символ Unicode.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Умный указатель на объект, упаковывающий значение для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, используемый, если тип упакованного значения — [String](../../string/). |

### Возвращаемое значение

Символ Unicode, эквивалентный указанному упакованному значению.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)