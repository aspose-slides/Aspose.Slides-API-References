---
title: StartsWith()
second_title: Aspose.Slides for C++ API Reference
description: Checks if string begins with specified substring.
type: docs
weight: 443
url: /cpp/system/string/startswith/
---
## String::StartsWith(const String\&) const method


Checks if string begins with specified substring.

```cpp
bool System::String::StartsWith(const String &value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Lookup string. |

### Return Value

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, System::StringComparison) const method


Checks if string begins with specified substring.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Lookup string. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, see [System::StringComparison](../../stringcomparison/) for details. |

### Return Value

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method


Checks if string begins with specified substring.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Lookup string. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use while performing string comparison. |

### Return Value

true if string starts with specified substring, false otherwise.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)