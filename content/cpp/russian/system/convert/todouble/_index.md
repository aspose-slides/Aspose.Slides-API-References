---
title: ToDouble()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное логическое значение в эквивалентное значение двойной точности с плавающей запятой.
type: docs
weight: 222
url: /ru/system/convert/todouble/
---
## Convert::ToDouble(bool) метод


Преобразует указанное логическое значение в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) метод


Преобразует указанное 8-битное беззнаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) метод


Преобразует указанное 8-битное знаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) метод


Преобразует указанное 16-битное беззнаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) метод


Преобразует указанное 16-битное знаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) метод


Преобразует указанное 32-битное беззнаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) метод


Преобразует указанное 32-битное знаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) метод


Преобразует указанное 64-битное беззнаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) метод


Преобразует указанное 64-битное знаковое целое число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) метод


Преобразует указанное число одинарной точности в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) метод


Возвращает указанное число двойной точности.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) метод


Преобразует указанное десятичное число в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) метод


Преобразует указанную нулевую строку в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Возвращаемое значение

Ноль.

## Convert::ToDouble(const char_t *) метод


Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Аргументы

| Параметр | Type | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

Значение двойной точности, равное числу, представленному указанной C-строкой

## Convert::ToDouble(const String\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение двойной точности с плавающей запятой.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Аргументы

| Параметр | Type | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

Значение двойной точности, равное числу, представленному указанной строкой

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение двойной точности с плавающей запятой, используя предоставленную информацию о форматировании.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Type | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Значение двойной точности, равное числу, представленному указанной строкой

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) метод




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение двойной точности с плавающей запятой, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Type | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Битовая комбинация значений перечисления NumberStyles, определяющая разрешённый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Значение двойной точности, равное числу, представленному указанной строкой

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) метод 




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанное упакованное значение в значение двойной точности с плавающей запятой. Если тип упакованного значения — [String](../../string/), при преобразовании используется указанный строковый формат.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Аргументы

| Параметр | Type | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Умный указатель на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Строковый формат, используемый если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

Значение двойной точности, эквивалентное указанному упакованному значению

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)