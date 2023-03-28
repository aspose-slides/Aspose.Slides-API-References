---
title: Create()
second_title: Aspose.Slides for C++ API Reference
description: Creates culture-specific comparer.
type: docs
weight: 79
url: /cpp/system/stringcomparer/create/
---
## StringComparer::Create(const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, **bool**) method


Creates culture-specific comparer.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to create comparer for. |
| ignoreCase | **bool** | Whether the comparer should ignore case. |

### Return Value

Pointer to newly created comparer object.

## See Also

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [StringComparer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
