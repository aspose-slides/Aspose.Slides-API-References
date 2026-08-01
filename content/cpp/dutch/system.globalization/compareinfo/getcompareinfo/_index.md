---
title: GetCompareInfo()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt CompareInfo op die geassocieerd is met de opgegeven cultuur en die stringvergelijkingsmethoden gebruikt in de opgegeven assembly.
type: docs
weight: 183
url: /nl/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) methode


Haalt [CompareInfo](../) op die geassocieerd is met de opgegeven cultuur en die stringvergelijkingsmethoden gebruikt in de opgegeven assembly.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| culture | int | Cultuuridentificatie (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly die methoden voor stringvergelijking bevat. |

### Retourwaarde

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) methode


Haalt [CompareInfo](../) op die geassocieerd is met de opgegeven cultuur en die stringvergelijkingsmethoden gebruikt in de opgegeven assembly.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Cultuurnaam. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly die methoden voor stringvergelijking bevat. |

### Retourwaarde

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(int) methode


Haalt [CompareInfo](../) op die geassocieerd is met de opgegeven cultuur.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| culture | int | Cultuuridentificatie (LCID). |

### Retourwaarde

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&) methode


Haalt [CompareInfo](../) op die geassocieerd is met de opgegeven cultuur.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Cultuurnaam. |

### Retourwaarde

[CompareInfo](../) object.

## Zie ook

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Assembly](../../../system.reflection/assembly/)
* Klasse [CompareInfo](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Globalization](../../)
* Library [Aspose.Slides](../../../)