---
title: TryParse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение Decimal.
type: docs
weight: 482
url: /ru/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../).

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| result | [Decimal](../)\& | Ссылка на переменную [Decimal](../), в которой помещается результат преобразования |

### Возвращаемое значение

True, если преобразование удалось, иначе — false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) метод

Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../) с использованием предоставленной информации о форматировании и стиля числа.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Побитовое комбинирование значений перечисления NumberStyles, которое указывает разрешённый стиль строкового представления числа |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Указатель на объект, содержащий информацию о строковом формате |
| result | [Decimal](../)\& | Выходной параметр; содержит результат преобразования |

### Возвращаемое значение

True, если преобразование удалось, иначе — false

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Тип-определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Decimal](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)