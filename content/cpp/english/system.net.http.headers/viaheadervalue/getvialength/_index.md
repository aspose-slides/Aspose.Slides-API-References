---
title: GetViaLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the ViaHeaderValue class.
type: docs
weight: 131
url: /system.net.http.headers/viaheadervalue/getvialength/
---
## ViaHeaderValue::GetViaLength(String, int32_t, System::SharedPtr\<Object\>\&) method


Converts a passed string from the specified index to an instance of the [ViaHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::ViaHeaderValue::GetViaLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | An instance where a parsed object will be assigned. |

### Return Value

Returns the length of a parsed substring, otherwise 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [ViaHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)