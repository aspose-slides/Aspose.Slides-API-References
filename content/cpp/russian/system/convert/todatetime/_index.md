---
title: ToDateTime()
second_title: Справочник по API Aspose.Slides для C++
description: Преобразование не поддерживается. Всегда генерирует InvalidCastException.
type: docs
weight: 248
url: /ru/system/convert/todatetime/
---
## Convert::ToDateTime(bool) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) метод

Возвращает указанную дату и время.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) метод

Преобразует указанную строку в экземпляр класса [DateTime](../../datetime/).

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

Экземпляр класса [DateTime](../../datetime/) , представляющий дату и время, указанные в переданной строке.

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку в экземпляр класса [DateTime](../../datetime/) с использованием предоставленной информации о форматировании.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Экземпляр класса [DateTime](../../datetime/) , представляющий дату и время, указанные в переданной строке.

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) метод




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) метод




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанное упакованное значение в эквивалентное значение [DateTime](../../datetime/).

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | SharedPtr к объекту, упаковывающему значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, который будет использоваться, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

Значение [DateTime](../../datetime/), эквивалентное указанному упакованному значению

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)