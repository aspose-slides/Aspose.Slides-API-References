---
title: GetCacheControlLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the CacheControlHeaderValue class.
type: docs
weight: 456
url: /cpp/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [CacheControlHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | A value that must be added to the parsed object. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

The length of a parsed substring, otherwise 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [CacheControlHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)