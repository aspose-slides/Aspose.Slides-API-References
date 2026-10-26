---
title: GetCompareInfo()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft CompareInfo ab, die mit der angegebenen Kultur verknüpft ist und String-Vergleichsmethoden in der angegebenen Assembly verwendet.
type: docs
weight: 183
url: /de/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) Methode

Ruft [CompareInfo](../) ab, die mit der angegebenen Kultur verknüpft ist und String-Vergleichsmethoden in der angegebenen Assembly verwendet.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| culture | int | Kulturbezeichner (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly, die String-Vergleichsmethoden enthält. |

### Rückgabewert

[CompareInfo](../) Objekt.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) Methode

Ruft [CompareInfo](../) ab, die mit der angegebenen Kultur verknüpft ist und String-Vergleichsmethoden in der angegebenen Assembly verwendet.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kulturname. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly, die String-Vergleichsmethoden enthält. |

### Rückgabewert

[CompareInfo](../) Objekt.

## CompareInfo::GetCompareInfo(int) Methode

Ruft [CompareInfo](../) ab, die mit der angegebenen Kultur verknüpft ist.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| culture | int | Kulturbezeichner (LCID). |

### Rückgabewert

[CompareInfo](../) Objekt.

## CompareInfo::GetCompareInfo(const String\&) Methode

Ruft [CompareInfo](../) ab, die mit der angegebenen Kultur verknüpft ist.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kulturname. |

### Rückgabewert

[CompareInfo](../) Objekt.

## Siehe auch

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Assembly](../../../system.reflection/assembly/)
* Klasse [CompareInfo](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Globalization](../../)
* Library [Aspose.Slides](../../../)