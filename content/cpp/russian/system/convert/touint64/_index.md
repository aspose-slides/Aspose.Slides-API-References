---
title: ToUInt64()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное логическое значение в эквивалентное 64-битное беззнаковое целое число.
type: docs
weight: 196
url: /ru/system/convert/touint64/
---
## Convert::ToUInt64(bool) метод

Преобразует указанное логическое значение в эквивалентное 64-битное беззнаковое целое число.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) метод

Преобразует указанное 8-битное беззнаковое целое число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) метод

Преобразует указанное 8-битное знаковое целое число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) метод

Преобразует указанное 16-битное беззнаковое целое число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) метод

Преобразует указанное 16-битное знаковое целое число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) метод

Преобразует указанное 32-битное беззнаковое целое число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) метод

Преобразует указанное 32-битное знаковое целое число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) метод

Возвращает указанное 64-битное беззнаковое целое число.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) метод

Преобразует указанное 64-битное знаковое целое число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) метод

Преобразует указанное число с плавающей запятой одинарной точности в эквивалентное 64-битное беззнаковое целое число.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) метод

Преобразует указанное число с плавающей запятой двойной точности в эквивалентное 64-битное беззнаковое целое число.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal&) метод

Преобразует указанное десятичное число в эквивалентное 64-битное беззнаковое целое число.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) метод

Преобразует указанный символ Unicode в эквивалентное 64-битное беззнаковое целое число.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) метод

Преобразует указанную нулевую строку в эквивалентное беззнаковое 64-битное целое значение.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```

### Возвращаемое значение

Ноль.

## Convert::ToUInt64(const char_t *) метод

Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое значение.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, равное числу, представленному указанной C-строкой

## Convert::ToUInt64(const String&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое значение.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToUInt64(const String&, int) метод

Преобразует указанную строку, содержащую строковое представление числа в заданной системе счисления, в эквивалентное беззнаковое 64-битное целое значение.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| from_base | int | Основание числа, представляющегося строкой |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToUInt64(const String&, const SharedPtr<IFormatProvider>&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое значение, используя предоставленную информацию о форматировании.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToUInt64(const String&, const SharedPtr<Globalization::CultureInfo>&) метод

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String&, const SharedPtr<Globalization::NumberFormatInfo>&) метод

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String&, std::nullptr_t) метод

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое значение, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое объединение значений перечисления NumberStyles, определяющее разрешённый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToUInt64(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&) метод

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&) метод

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String&, Globalization::NumberStyles, std::nullptr_t) метод

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) метод

```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr<Object>&, const SharedPtr<IFormatProvider>&) метод

Преобразует указанное упакованное значение в эквивалентное беззнаковое 64-битное целое значение.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Умный указатель на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, который будет использоваться, если тип упакованного значения – [String](../../string/) |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, эквивалентное указанному упакованному значению

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