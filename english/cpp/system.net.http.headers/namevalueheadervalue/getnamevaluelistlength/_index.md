---
title: GetNameValueListLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to the collection of the NameValueHeaderValue-class instances and returns the length of a parsed substring.
type: docs
weight: 131
url: /cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method


Converts a passed string from the specified index to the collection of the NameValueHeaderValue-class instances and returns the length of a parsed substring.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to analyze. |
| startIndex | **int32_t** | A start position for analyzing. |
| delimiter | char16_t | A string that is used to delimit items in the specified string. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | The output parameter where a parsed collection will be assigned. |

### Return Value

The length of a parsed substring.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)