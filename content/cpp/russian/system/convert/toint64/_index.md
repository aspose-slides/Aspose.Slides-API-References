---
title: ToInt64()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное логическое значение в эквивалентное 64-битное знаковое целое число.
type: docs
weight: 183
url: /ru/system/convert/toint64/
---
## Convert::ToInt64(bool) метод

Преобразует указанное логическое значение в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) метод

Преобразует указанное 8-битное беззнаковое целое число в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) метод

Преобразует указанное 8-битное знаковое целое число в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) метод

Преобразует указанное 16-битное беззнаковое целое число в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) метод

Преобразует указанное 16-битное знаковое целое число в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) метод

Преобразует указанное 32-битное беззнаковое целое число в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) метод

Преобразует указанное 32-битное знаковое целое число в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) метод

Преобразует указанное 64-битное беззнаковое целое число в эквивалентное 64-битное знаковое целое число.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) метод

Возвращает указанное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) метод

Преобразует указанное число типа float в эквивалентное 64-битное знаковое целое число.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) метод

Преобразует указанное число типа double в эквивалентное 64-битное знаковое целое число.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) метод

Преобразует указанное десятичное число в эквивалентное 64-битное знаковое целое число.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) метод

Преобразует указанный unicode-символ в эквивалентное 64-битное знаковое целое число.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) метод

Преобразует указанную нуль-строку в эквивалентное значение 64-битного целого числа.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### Возвращаемое значение

Ноль.

## Convert::ToInt64(const char_t *) метод

Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное 64-битное целое значение.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

64-битное целочисленное значение, равное числу, представленному указанной C-строкой

## Convert::ToInt64(const String\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное целое значение.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

64-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt64(const String\&, int) метод

Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное 64-битное целое значение.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| from_base | int | Основание числа, представленного строкой |

### Возвращаемое значение

64-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное целое значение с использованием предоставленной информации о форматировании.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

64-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) метод

```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное целое значение с использованием предоставленной информации о форматировании и стиля числа.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовая комбинация значений перечисления NumberStyles, указывающая разрешённый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

64-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) метод

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) метод

```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанное упакованное значение в эквивалентное 64-битное целое значение.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Разделяемый указатель на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Строковый формат, который будет использоваться, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

64-битное целочисленное значение, эквивалентное указанному упакованному значению

## См. также

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)