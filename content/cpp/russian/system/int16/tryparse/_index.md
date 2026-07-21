---
title: TryParse()
second_title: Aspose.Slides для C++ API справка
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое.
type: docs
weight: 14
url: /ru/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **int16_t**\& | Ссылка на 16-разрядную знаковую целочисленную переменную, в которую помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование удалось, иначе - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) метод


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-разрядное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовая комбинация значений перечисления NumberStyles, указывающая допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **int16_t**\& | Ссылка на 16-разрядную знаковую целочисленную переменную, в которую помещается результат преобразования. |

### Возвращаемое значение

True, если преобразование удалось, иначе - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) метод




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) метод




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) метод




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Тип-определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Int16](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)