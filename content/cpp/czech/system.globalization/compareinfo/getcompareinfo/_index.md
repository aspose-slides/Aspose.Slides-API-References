---
title: GetCompareInfo()
second_title: Aspose.Slides pro C++ – reference API
description: Získá CompareInfo spojený se zadanou kulturou a používající metody porovnávání řetězců ve specifikovaném sestavení.
type: docs
weight: 183
url: /cs/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) metoda

Získá [CompareInfo](../) spojený se zadanou kulturou a používající metody porovnávání řetězců ve specifikovaném sestavení.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| culture | int | Identifikátor kultury (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Sestavení, které obsahuje metody porovnávání řetězců. |

### Návratová hodnota

[CompareInfo](../) objekt.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) metoda

Získá [CompareInfo](../) spojený se zadanou kulturou a používající metody porovnávání řetězců ve specifikovaném sestavení.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název kultury. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Sestavení, které obsahuje metody porovnávání řetězců. |

### Návratová hodnota

[CompareInfo](../) objekt.

## CompareInfo::GetCompareInfo(int) metoda

Získá [CompareInfo](../) spojený se zadanou kulturou.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| culture | int | Identifikátor kultury (LCID). |

### Návratová hodnota

[CompareInfo](../) objekt.

## CompareInfo::GetCompareInfo(const String\&) metoda

Získá [CompareInfo](../) spojený se zadanou kulturou.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název kultury. |

### Návratová hodnota

[CompareInfo](../) objekt.

## Viz také

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Assembly](../../../system.reflection/assembly/)
* Třída [CompareInfo](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Globalization](../../)
* Knihovna [Aspose.Slides](../../../)