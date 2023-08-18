---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API Reference
description: Gets CompareInfo associated with the specified culture and using string comparison methods in the specified assembly.
type: docs
weight: 183
url: /system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) method


Gets [CompareInfo](../) associated with the specified culture and using string comparison methods in the specified assembly.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Return Value

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) method


Gets [CompareInfo](../) associated with the specified culture and using string comparison methods in the specified assembly.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Return Value

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(int) method


Gets [CompareInfo](../) associated with the specified culture.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |

### Return Value

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&) method


Gets [CompareInfo](../) associated with the specified culture.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |

### Return Value

[CompareInfo](../) object.

## See Also

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Assembly](../../../system.reflection/assembly/)
* Class [CompareInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)