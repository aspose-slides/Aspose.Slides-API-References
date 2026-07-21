---
title: Parse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное знаковое целое.
type: docs
weight: 1
url: /ru/system/sbyte/parse/
---
## SByte::Parse(const String\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное знаковое целое.

```cpp
static int8_t System::SByte::Parse(const String &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |

### Возвращаемое значение

8-битное знаковое целое, равное числу, представленному в указанной строке.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное знаковое целое, используя предоставленную информацию о форматировании.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Возвращаемое значение

8-битное знаковое целое, равное числу, представленному в указанной строке.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) метод




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Битовая комбинация значений перечисления NumberStyles, указывающая разрешённый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |

### Возвращаемое значение

8-битное знаковое целое, равное числу, представленному в указанной строке.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) метод




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Структура [SByte](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)