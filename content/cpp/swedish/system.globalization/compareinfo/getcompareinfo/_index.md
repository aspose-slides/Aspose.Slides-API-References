---
title: GetCompareInfo()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar CompareInfo som är associerad med den specificerade kulturen och använder strängjämförelsesmetoder i den specificerade assemblyn.
type: docs
weight: 183
url: /sv/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) metod


Hämtar [CompareInfo](../) som är associerad med den angivna kulturen och använder strängjämförelsesmetoder i den angivna assemblyn.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| culture | int | Kulturidentifierare (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly som innehåller strängjämförelsesmetoder. |

### Returvärde

[CompareInfo](../) objekt.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) metod


Hämtar [CompareInfo](../) som är associerad med den angivna kulturen och använder strängjämförelsesmetoder i den angivna assemblyn.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kulturnamn. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly som innehåller strängjämförelsesmetoder. |

### Returvärde

[CompareInfo](../) objekt.

## CompareInfo::GetCompareInfo(int) metod


Hämtar [CompareInfo](../) som är associerad med den angivna kulturen.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| culture | int | Kulturidentifierare (LCID). |

### Returvärde

[CompareInfo](../) objekt.

## CompareInfo::GetCompareInfo(const String\&) metod


Hämtar [CompareInfo](../) som är associerad med den angivna kulturen.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kulturnamn. |

### Returvärde

[CompareInfo](../) objekt.

## Se också

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Assembly](../../../system.reflection/assembly/)
* Klass [CompareInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Globalization](../../)
* Bibliotek [Aspose.Slides](../../../)