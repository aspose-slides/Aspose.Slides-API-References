---
title: GetCompareInfo()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Zwraca CompareInfo powiązany z określoną kulturą i używający metod porównywania ciągów znaków w określonym zestawie.
type: docs
weight: 183
url: /pl/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) metoda

Otrzymuje [CompareInfo](../) powiązany z określoną kulturą i używający metod porównywania ciągów znaków w określonym zestawie.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| culture | int | Identyfikator kultury (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Zestaw zawierający metody porównywania ciągów znaków. |

### Wartość zwracana

[CompareInfo](../) obiekt.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) metoda

Otrzymuje [CompareInfo](../) powiązany z określoną kulturą i używający metod porównywania ciągów znaków w określonym zestawie.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa kultury. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Zestaw zawierający metody porównywania ciągów znaków. |

### Wartość zwracana

[CompareInfo](../) obiekt.

## CompareInfo::GetCompareInfo(int) metoda

Otrzymuje [CompareInfo](../) powiązany z określoną kulturą.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| culture | int | Identyfikator kultury (LCID). |

### Wartość zwracana

[CompareInfo](../) obiekt.

## CompareInfo::GetCompareInfo(const String\&) metoda

Otrzymuje [CompareInfo](../) powiązany z określoną kulturą.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa kultury. |

### Wartość zwracana

[CompareInfo](../) obiekt.

## Zobacz także

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Assembly](../../../system.reflection/assembly/)
* Klasa [CompareInfo](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Globalization](../../)
* Biblioteka [Aspose.Slides](../../../)