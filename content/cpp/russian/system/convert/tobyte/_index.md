---
title: ToByte()
second_title: Aspose.Slides для C++ справка API
description: Преобразует указанное логическое значение в эквивалентное 8-битное беззнаковое целое.
type: docs
weight: 92
url: /ru/system/convert/tobyte/
---
## Convert::ToByte(bool) метод

Преобразует указанное логическое значение в эквивалентное 8-битное беззнаковое целое.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) метод

Возвращает указанное 8-битное беззнаковое целое.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) метод

Преобразует указанное 8-битное знаковое целое в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) метод

Преобразует указанное 16-битное беззнаковое целое в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) метод

Преобразует указанное 16-битное знаковое целое в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) метод


Преобразует указанное 32-битное беззнаковое целое в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) метод


Преобразует указанное 32-битное знаковое целое в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) метод


Преобразует указанное 64-битное беззнаковое целое в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) метод


Преобразует указанное 64-битное знаковое целое в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) метод


Преобразует указанное число с плавающей точкой одинарной точности в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) метод


Преобразует указанное число с плавающей точкой двойной точности в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) метод


Преобразует указанное десятичное число в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) метод


Преобразует указанный Unicode-символ в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) метод


Преобразует указанную нулевую строку в эквивалентное беззнаковое 8-битное целое.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```


### Возвращаемое значение

Ноль.

## Convert::ToByte(const char_t *) метод


Преобразует указанную c-строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

Беззнаковое 8-битное целое, равное числу, представленному указанной c-строкой

## Convert::ToByte(const String\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

Беззнаковое 8-битное целое, равное числу, представленному указанной строкой

## Convert::ToByte(const String\&, int) метод


Преобразует указанную строку, содержащую строковое представление числа в заданной системе счисления, в эквивалентное беззнаковое 8-битное целое.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| from_base | int | Основание системы счисления числа, представленного строкой |

### Возвращаемое значение

Беззнаковое 8-битное целое, равное числу, представленному указанной строкой

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое, используя предоставленную информацию о форматировании.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Беззнаковое 8-битное целое, равное числу, представленному указанной строкой

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) метод




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, определяющее допустимый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Беззнаковое 8-битное целое, равное числу, представленному указанной строкой

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) метод




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) метод




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанное упакованное значение в эквивалентное беззнаковое 8-битное целое.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Указатель `shared_ptr` на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, используемый, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

Беззнаковое 8-битное целое, эквивалентное указанному упакованному значению

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