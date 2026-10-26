---
title: StartsWith()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, начинается ли строка с указанной подстрокой.
type: docs
weight: 469
url: /ru/system/string/startswith/
---
## String::StartsWith(const String\&) const метод

Проверяет, начинается ли строка с указанной подстроки.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Искомая строка. |

### Возвращаемое значение

true если строка начинается с указанной подстроки, false в противном случае.

## String::StartsWith(const String\&, System::StringComparison) const метод

Проверяет, начинается ли строка с указанной подстроки.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Искомая строка. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим, см. [System::StringComparison](../../stringcomparison/) для деталей. |

### Возвращаемое значение

true если строка начинается с указанной подстроки, false в противном случае.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const метод

Проверяет, начинается ли строка с указанной подстроки.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Искомая строка. |
| ignoreCase | **bool** | Указывает, является ли сравнение нечувствительным к регистру. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при выполнении сравнения строк. |

### Возвращаемое значение

true если строка начинается с указанной подстроки, false в противном случае.

## См. также

* Перечисление [StringComparison](../../stringcomparison/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [String](../)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)