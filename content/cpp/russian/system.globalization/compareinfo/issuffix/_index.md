---
title: IsSuffix()
second_title: Aspose.Slides для C++ справка по API
description: Проверяет, заканчивается ли указанная строка указанным суффиксом с использованием заданных параметров сравнения.
type: docs
weight: 118
url: /ru/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const method

Проверяет, заканчивается ли указанная строка указанным суффиксом с использованием заданных параметров сравнения.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | Исходная строка. |
| suffix | const [String](../../../system/string/)\& | Строка суффикса. |
| options | [CompareOptions](../../compareoptions/) | Параметры сравнения. |

### Возвращаемое значение

True if string ends with suffix; otherwise false.

## CompareInfo::IsSuffix(const String\&, const String\&) const method

Проверяет, заканчивается ли указанная строка указанным суффиксом.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | Исходная строка. |
| suffix | const [String](../../../system/string/)\& | Строка суффикса. |

### Возвращаемое значение

True if string ends with suffix; otherwise false.

## См. также

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)