---
title: Parse()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное беззнаковое целое.
type: docs
weight: 1
url: /ru/system/byte/parse/
---
## Byte::Parse(const String\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное беззнаковое целое.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |

### Возвращаемое значение

8-битное беззнаковое целое, равное числу, представленного указанной строкой.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное беззнаковое целое, используя предоставленную информацию о форматировании.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о строковом формате. |

### Возвращаемое значение

8-битное беззнаковое целое, равное числу, представленного указанной строкой.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) метод




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, задающее допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о строковом формате. |

### Возвращаемое значение

8-битное беззнаковое целое, равное числу, представленного указанной строкой.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) метод




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) метод 




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) метод 




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Тип [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Byte](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)