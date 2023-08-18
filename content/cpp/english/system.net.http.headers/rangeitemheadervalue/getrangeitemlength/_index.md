---
title: GetRangeItemLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the RangeItemHeaderValue class.
type: docs
weight: 92
url: /system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [RangeItemHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

Returns the length of a parsed substring, otherwise 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)