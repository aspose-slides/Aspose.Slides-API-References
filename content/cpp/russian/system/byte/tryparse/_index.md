---
title: TryParse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное беззнаковое целое.
type: docs
weight: 14
url: /ru/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) метод


Преобразует заданную строку, содержащую строковое представление числа, в эквивалентное 8-битное беззнаковое целое.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **uint8_t**\& | Ссылка на переменную беззнакового 8-битного целого, куда помещается результат преобразования. |

### Возвращаемое значение

True если преобразование успешно, иначе — false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) метод


Преобразует заданную строку, содержащую строковое представление числа, в эквивалентное 8-битное беззнаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, указывающее допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **uint8_t**\& | Ссылка на переменную беззнакового 8-битного целого, куда помещается результат преобразования. |

### Возвращаемое значение

True если преобразование успешно, иначе — false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) метод




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) метод




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) метод




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## См. также

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)