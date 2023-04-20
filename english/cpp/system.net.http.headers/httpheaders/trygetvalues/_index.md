---
title: TryGetValues()
second_title: Aspose.Slides for C++ API Reference
description: Tries to get corresponding values by the specified name.
type: docs
weight: 66
url: /cpp/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) method


Tries to get corresponding values by the specified name.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The header name. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | An instance where corresponding values will be assigned. |

### Return Value

True when the header values are found by the specified name, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)