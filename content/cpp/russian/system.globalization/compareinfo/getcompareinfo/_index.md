---
title: GetCompareInfo()
second_title: Справочник API Aspose.Slides для C++
description: Получает объект CompareInfo, связанный с указанной культурой и использующий методы сравнения строк в указанной сборке.
type: docs
weight: 183
url: /ru/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) метод

Получает [CompareInfo](../), связанный с указанной культурой и использующий методы сравнения строк в указанной сборке.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Возвращаемое значение

[CompareInfo](../) объект.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) метод

Получает [CompareInfo](../), связанный с указанной культурой и использующий методы сравнения строк в указанной сборке.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Возвращаемое значение

[CompareInfo](../) объект.

## CompareInfo::GetCompareInfo(int) метод

Получает [CompareInfo](../), связанный с указанной культурой.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |

### Возвращаемое значение

[CompareInfo](../) объект.

## CompareInfo::GetCompareInfo(const String\&) метод

Получает [CompareInfo](../), связанный с указанной культурой.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |

### Возвращаемое значение

[CompareInfo](../) объект.

## См. также

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Assembly](../../../system.reflection/assembly/)
* Класс [CompareInfo](../)
* Класс [String](../../../system/string/)
* Пространство имен [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)