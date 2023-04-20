---
title: GetMediaTypeLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the MediaTypeHeaderValue class.
type: docs
weight: 144
url: /cpp/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [MediaTypeHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | The delegate that is used to create instances of the [MediaTypeHeaderValue](../) class. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

Returns the length of a parsed substring, otherwise 0.

## See Also

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)