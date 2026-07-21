---
title: ToInt32()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное логическое значение в эквивалентное 32-битное знаковое целое число.
type: docs
weight: 157
url: /ru/system/convert/toint32/
---
## Convert::ToInt32(bool) метод

Преобразует указанное логическое значение в эквивалентное 32-битное знаковое целое число.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) метод

Преобразует указанное 8-битное беззнаковое целое число в эквивалентное 32-битное знаковое целое число.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) метод

Преобразует указанное 8-битное знаковое целое число в эквивалентное 32-битное знаковое целое число.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) метод

Преобразует указанное 16-битное беззнаковое целое число в эквивалентное 32-битное знаковое целое число.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) метод

Преобразует указанное 16-битное знаковое целое число в эквивалентное 32-битное знаковое целое число.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) метод

Преобразует указанное 32-битное беззнаковое целое число в эквивалентное 32-битное знаковое целое число.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) метод

Возвращает указанное 32-битное знаковое целое число.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) метод

Преобразует указанное 64-битное беззнаковое целое число в эквивалентное 32-битное знаковое целое число.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) метод

Преобразует указанное 64-битное знаковое целое число в эквивалентное 32-битное знаковое целое число.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) метод

Преобразует указанное число с плавающей точкой (float) в эквивалентное 32-битное знаковое целое число.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) метод

Преобразует указанное число с плавающей точкой (double) в эквивалентное 32-битное знаковое целое число.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) метод

Преобразует указанное десятичное число в эквивалентное 32-битное знаковое целое число.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) метод

Преобразует указанный юникод-символ в эквивалентное 32-битное знаковое целое число.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) метод

Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) метод

Преобразует указанную нулевую строку в эквивалентное 32-битное целочисленное значение.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Возвращаемое значение

Ноль.

## Convert::ToInt32(const char_t *) метод

Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное 32-битное целочисленное значение.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

32-битное целочисленное значение, равное числу, представленному указанной C-строкой

## Convert::ToInt32(const String\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное целочисленное значение.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

32-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt32(const String\&, int) метод

Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное 32-битное целочисленное значение.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| from_base | int | Основание числа, представленного строкой |

### Возвращаемое значение

32-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное целочисленное значение, используя предоставленную информацию о форматировании.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

32-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) метод

```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное целочисленное значение, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Битовая комбинация значений перечисления NumberStyles, определяющая разрешённый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

32-битное целочисленное значение, равное числу, представленному указанной строкой

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) метод

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) метод

```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует указанное упакованное значение в эквивалентное 32-битное целочисленное значение.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Умный указатель на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, используемый, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

32-битное целочисленное значение, эквивалентное указанному упакованному значению

## Смотрите также

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