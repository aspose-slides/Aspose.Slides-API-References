---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the RangeHeaderValue class.
type: docs
weight: 105
url: /system.net.http.headers/rangeheadervalue/tryparse/
---
## RangeHeaderValue::TryParse(String, System::SharedPtr\<RangeHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [RangeHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::RangeHeaderValue::TryParse(String input, System::SharedPtr<RangeHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)