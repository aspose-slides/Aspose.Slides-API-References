---
title: Parse()
second_title: Справочник по API Aspose.Slides для C++
description: Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса Decimal.
type: docs
weight: 469
url: /ru/system/decimal/parse/
---
## Decimal::Parse(const String\&) метод

Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление числа |

### Возвращаемое значение

Новый экземпляр класса [Decimal](../), представляющий значение, эквивалентное тому, которое представлено указанной строкой.

## Decimal::Parse(const String\&, Globalization::NumberStyles) метод

Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](../) с использованием указанного стиля.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление десятичного значения для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Битовое сочетание значений перечисления, которое предоставляет дополнительную информацию о **s**, о стилевых элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [Decimal](../) |

### Возвращаемое значение

Новый экземпляр класса [Decimal](../), представляющий значение, эквивалентное тому, которое представлено указанной строкой.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](../) с использованием указанного поставщика формата.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление десятичного значения для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата |

### Возвращаемое значение

Новый экземпляр класса [Decimal](../), представляющий значение, эквивалентное тому, которое представлено указанной строкой.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) метод

Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](../) с использованием указанного стиля и поставщика формата.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление десятичного значения для преобразования |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Битовое сочетание значений перечисления, которое предоставляет дополнительную информацию о **s**, о стилевых элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата |

### Возвращаемое значение

Новый экземпляр класса [Decimal](../), представляющий значение, эквивалентное тому, которое представлено указанной строкой.

## См. также

* Перечисление [NumberStyles](../../../system.globalization/numberstyles/)
* Тип-определение [SharedPtr](../../sharedptr/)
* Класс [Decimal](../)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)