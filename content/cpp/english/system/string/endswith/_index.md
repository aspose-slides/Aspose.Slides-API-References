---
title: EndsWith()
second_title: Aspose.Slides for C++ API Reference
description: Checks if string ends with specified substring.
type: docs
weight: 456
url: /system/string/endswith/
---
## String::EndsWith(const String\&) const method


Checks if string ends with specified substring.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Lookup string. |

### Return Value

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, System::StringComparison) const method


Checks if string ends with specified substring.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Lookup string. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, see [System::StringComparison](../../stringcomparison/) for details. |

### Return Value

true if string ends with specified substring, false otherwise.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method


Checks if string ends with specified substring.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Lookup string. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use while performing string comparison. |

### Return Value

true if string ends with specified substring, false otherwise.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)