---
title: ToSByte()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное логическое значение в эквивалентное 8-битное знаковое целое число.
type: docs
weight: 105
url: /ru/system/convert/tosbyte/
---
## Convert::ToSByte(bool) метод


Преобразует указанное логическое значение в эквивалентное 8-битное знаковое целое число.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) метод


Преобразует указанное 8-битное беззнаковое целое в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) метод


Возвращает указанное 8-битное знаковое целое число.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) метод


Преобразует указанное 16-битное беззнаковое целое в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) метод


Преобразует указанное 16-битное знаковое целое в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) метод


Преобразует указанное 32-битное беззнаковое целое в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) метод


Преобразует указанное 32-битное знаковое целое в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) метод


Преобразует указанное 64-битное беззнаковое целое в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) метод


Преобразует указанное 64-битное знаковое целое в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) метод


Преобразует указанное число с плавающей запятой одинарной точности в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) метод


Преобразует указанное число с плавающей запятой двойной точности в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) метод


Преобразует указанное десятичное число в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) метод


Преобразует указанный Unicode-символ в эквивалентное 8-битное знаковое целое число.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) метод


Преобразование не поддерживается. Всегда генерирует InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) метод


Преобразует указанную нулевую строку в эквивалентное 8-битное целое значение.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```


### Возвращаемое значение

Ноль.

## Convert::ToSByte(const char_t *) метод


Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное 8-битное целое значение.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка, которую нужно преобразовать |

### Возвращаемое значение

8-битное целое значение, равное числу, представленному указанной C-строкой

## Convert::ToSByte(const String\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное целое значение.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка, которую нужно преобразовать |

### Возвращаемое значение

8-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToSByte(const String\&, int) метод


Преобразует указанную строку, содержащую строковое представление числа в заданной системе счисления, в эквивалентное 8-битное целое значение.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка, которую нужно преобразовать |
| from_base | int | Основание системы счисления числа, представленного строкой |

### Возвращаемое значение

8-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое значение, используя предоставленную информацию о форматировании.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка, которую нужно преобразовать |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

8-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) метод




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное целое значение, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка, которую нужно преобразовать |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовая комбинация значений перечисления NumberStyles, определяющая допустимый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки |

### Возвращаемое значение

Беззнаковое 8-битное целое значение, равное числу, представленному указанной строкой

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) метод




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) метод




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанное упакованное значение в эквивалентное 8-битное целое значение.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Общий указатель на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, используемый, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

8-битное целое значение, эквивалентное указанному упакованному значению

## Смотрите также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [Decimal](../../decimal/)
* Класс [DateTime](../../datetime/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Класс [Object](../../object/)
* Структура [Convert](../)
* Структура [Enum](../../enum/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)