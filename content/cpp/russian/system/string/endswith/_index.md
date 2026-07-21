---
title: EndsWith()
second_title: Aspose.Slides для C++ API Reference
description: Проверяет, заканчивается ли строка указанной подстрокой.
type: docs
weight: 482
url: /ru/system/string/endswith/
---
## String::EndsWith(const String&) const метод


Проверяет, заканчивается ли строка указанной подстрокой.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Строка для поиска. |

### Возвращаемое значение

true если строка заканчивается указанной подстрокой, false в противном случае.

## String::EndsWith(const String&, System::StringComparison) const метод


Проверяет, заканчивается ли строка указанной подстрокой.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Строка для поиска. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | Режим [Comparison](../../comparison/), см. [System::StringComparison](../../stringcomparison/) для подробностей. |

### Возвращаемое значение

true если строка заканчивается указанной подстрокой, false в противном случае.

## String::EndsWith(const String&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const метод


Проверяет, заканчивается ли строка указанной подстрокой.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Строка для поиска. |
| ignoreCase | **bool** | Указывает, является ли сравнение нечувствительным к регистру. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при сравнении строк. |

### Возвращаемое значение

true если строка заканчивается указанной подстрокой, false в противном случае.

## См. также

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)