---
title: ToSingle()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное логическое значение в эквивалентное число одинарной точности с плавающей запятой.
type: docs
weight: 209
url: /ru/system/convert/tosingle/
---
## Convert::ToSingle(bool) метод


Преобразует указанное логическое значение в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) метод


Преобразует указанный 8-разрядный беззнаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) метод


Преобразует указанный 8-разрядный знаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) метод


Преобразует указанный 16-разрядный беззнаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) метод


Преобразует указанный 16-разрядный знаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) метод


Преобразует указанный 32-разрядный беззнаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) метод


Преобразует указанный 32-разрядный знаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) метод


Преобразует указанный 64-разрядный беззнаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) метод


Преобразует указанный 64-разрядный знаковый целочисленный тип в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) метод


Возвращает указанное число типа float.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) метод


Преобразует указанное число двойной точности в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) метод


Преобразует указанное десятичное число в эквивалентное число одинарной точности с плавающей запятой.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) метод


Преобразует указанную нулевую строку в эквивалентное значение одинарной точности с плавающей запятой.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```


### Возвращаемое значение

Ноль.

## Convert::ToSingle(const char_t *) метод


Преобразует указанную c-строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

Значение одинарной точности с плавающей запятой, равное числу, представленному указанной c-строкой

## Convert::ToSingle(const String\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой.

```cpp
static float System::Convert::ToSingle(const String &value)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

Значение одинарной точности с плавающей запятой, равное числу, представленному указанной строкой

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой, используя предоставленную информацию о форматировании.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Значение одинарной точности с плавающей запятой, равное числу, представленному указанной строкой

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) метод




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение одинарной точности с плавающей запятой, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, определяющее разрешённый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Значение одинарной точности с плавающей запятой, равное числу, представленному указанной строкой

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) метод




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанное упакованное значение в значение одинарной точности с плавающей запятой.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Умный указатель на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, который следует использовать, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

Значение одинарной точности с плавающей запятой, эквивалентное указанному упакованному значению

## See Also

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