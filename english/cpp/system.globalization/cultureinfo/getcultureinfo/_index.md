---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API Reference
description: Gets culture by its name. Same as CreateSpecificCulture.
type: docs
weight: 586
url: /cpp/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) method


Gets culture by its name. Same as CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Predefined culture name or existing culture object's name. |

### Return Value

Newly created culture object.

## CultureInfo::GetCultureInfo(const String\&, const String\&) method


Gets culture by its name.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Culture name used for [TextInfo](../../textinfo/) and [CompareInfo](../../compareinfo/) objects. |

### Return Value

Culture object.

## CultureInfo::GetCultureInfo(int32_t) method


Gets culture by id.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| culture | **int32_t** | Culture identifier. |

### Return Value

Newly created culture object.

## See Also

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Class [String](../../../system/string/)
* Class [CultureInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)