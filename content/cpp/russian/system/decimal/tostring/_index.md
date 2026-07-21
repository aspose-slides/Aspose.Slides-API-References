---
title: ToString()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает строковое представление значения, представленного объектом.
type: docs
weight: 352
url: /ru/system/decimal/tostring/
---
## Decimal::ToString() const метод


Возвращает строковое представление значения, представленного объектом.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const метод


Преобразует текущий объект в строку, используя специфичную для культуры информацию о формате.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий специфичную для культуры информацию о формате. |

### Возвращаемое значение

Строковое представление текущего объекта.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const метод




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const метод




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const метод




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const метод


Преобразует текущий объект в его строковое представление, используя указанный строковый формат и специфичную для культуры информацию о формате, предоставляемую указанным объектом [IFormatProvider](../../iformatprovider/).

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../string/)\& | Строковый формат. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий специфичную для культуры информацию о формате. |

### Возвращаемое значение

Строковое представление текущего объекта.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const метод




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const метод




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const метод




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## См. также

* Тип [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Decimal](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)