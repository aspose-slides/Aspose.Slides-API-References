---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the ViaHeaderValue class.
type: docs
weight: 118
url: /system.net.http.headers/viaheadervalue/tryparse/
---
## ViaHeaderValue::TryParse(String, System::SharedPtr\<ViaHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [ViaHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::ViaHeaderValue::TryParse(String input, System::SharedPtr<ViaHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ViaHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ViaHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)