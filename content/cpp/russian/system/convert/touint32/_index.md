---
title: ToUInt32()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанное булево значение в эквивалентное 32-битное беззнаковое целое.
type: docs
weight: 170
url: /ru/system/convert/touint32/
---
## Convert::ToUInt32(bool) метод


Преобразует указанное булево значение в эквивалентное 32-битное беззнаковое целое.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) метод


Преобразует указанное 8-битное беззнаковое целое в эквивалентное 32-битное беззнаковое целое.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) метод


Преобразует указанное 8-битное знаковое целое в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) метод


Преобразует указанное 16-битное беззнаковое целое в эквивалентное 32-битное беззнаковое целое.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) метод


Преобразует указанное 16-битное знаковое целое в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) метод


Возвращает указанное 32-битное беззнаковое целое.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) метод


Преобразует указанное 32-битное знаковое целое в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) метод


Преобразует указанное 64-битное беззнаковое целое в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) метод


Преобразует указанное 64-битное знаковое целое в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) метод


Преобразует указанное число с плавающей точкой одинарной точности в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) метод


Преобразует указанное число с плавающей точкой двойной точности в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) метод


Преобразует указанное десятичное число в эквивалентное 32-битное беззнаковое целое.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) метод


Преобразует указанный символ Unicode в эквивалентное 32-битное беззнаковое целое.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) метод


Преобразование не поддерживается. Всегда бросает InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) метод


Преобразует указанную нулевую строку в эквивалентное беззнаковое 32-битное целое.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```


### Возвращаемое значение

Ноль.

## Convert::ToUInt32(const char_t *) метод


Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

Беззнаковое 32-битное целое, равное числу, представленному указанной C-строкой

## Convert::ToUInt32(const String\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

Беззнаковое 32-битное целое, равное числу, представленному указанной строкой

## Convert::ToUInt32(const String\&, int) метод


Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное беззнаковое 32-битное целое.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| from_base | int | Основание системы счисления числа, представленного строкой |

### Возвращаемое значение

Беззнаковое 32-битное целое, равное числу, представленному указанной строкой

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое, используя предоставленную информацию о форматировании.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Беззнаковое 32-битное целое, равное числу, представленному указанной строкой

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) метод




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, определяющее разрешённый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Беззнаковое 32-битное целое, равное числу, представленному указанной строкой

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) метод




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) метод




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанное упакованное значение в эквивалентное беззнаковое 32-битное целое.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Указатель-разделяемый объект, содержащий упакованное значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, который будет использоваться, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

Беззнаковое 32-битное целое, эквивалентное указанному упакованному значению

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