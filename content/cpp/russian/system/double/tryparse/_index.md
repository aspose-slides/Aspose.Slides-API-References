---
title: TryParse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение типа double с двойной точностью.
type: docs
weight: 14
url: /ru/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение типа double с двойной точностью.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| result | **double**\& | Ссылка на переменную типа double с двойной точностью, в которую помещается результат преобразования. |

### Возвращаемое значение

True если преобразование удалось, иначе — false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение типа double с двойной точностью, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовая комбинация значений перечисления NumberStyles, указывающая допустимый стиль строкового представления числа. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о формате строки. |
| result | **double**\& | Ссылка на переменную типа double с двойной точностью, в которую помещается результат преобразования. |

### Возвращаемое значение

True если преобразование удалось, иначе — false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) метод




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) метод




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) метод




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Тип-определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Структура [Double](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)