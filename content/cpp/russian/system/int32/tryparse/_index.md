---
title: TryParse()
second_title: Aspose.Slides для C++ справка API
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное знаковое целое.
type: docs
weight: 14
url: /ru/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное знаковое целое.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **int32_t**\& | Ссылка на 32-битную знаковую целочисленную переменную, куда помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование удалось, иначе — false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, которое указывает разрешенный стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **int32_t**\& | Ссылка на 32-битную знаковую целочисленную переменную, куда помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование удалось, иначе — false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) метод




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) метод




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) метод




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## См. также

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)