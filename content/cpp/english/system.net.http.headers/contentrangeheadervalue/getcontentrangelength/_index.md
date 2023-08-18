---
title: GetContentRangeLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified position to an instance of the ContentRangeHeaderValue class.
type: docs
weight: 170
url: /system.net.http.headers/contentrangeheadervalue/getcontentrangelength/
---
## ContentRangeHeaderValue::GetContentRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) method


Converts a passed string from the specified position to an instance of the [ContentRangeHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | An instance where a parsed object will be assigned. |

### Return Value

The length of a parsed substring, otherwise 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [ContentRangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)