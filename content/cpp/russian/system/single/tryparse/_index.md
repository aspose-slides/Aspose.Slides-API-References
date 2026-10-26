---
title: TryParse()
second_title: Aspose.Slides для C++: справочник API
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение с одинарной точностью.
type: docs
weight: 14
url: /ru/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение с одинарной точностью.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **float**\& | Ссылка на переменную типа float, в которую будет помещён результат преобразования. |

### Возвращаемое значение

True, если преобразование удалось, иначе — false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение с одинарной точностью, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое сочетание значений перечисления NumberStyles, указывающее допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **float**\& | Ссылка на переменную типа float, в которую будет помещён результат преобразования. |

### Возвращаемое значение

True, если преобразование удалось, иначе — false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) метод




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) метод




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) метод




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Тип [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Структура [Single](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)