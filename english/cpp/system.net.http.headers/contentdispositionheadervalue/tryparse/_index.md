---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the ContentDispositionHeaderValue class.
type: docs
weight: 287
url: /cpp/system.net.http.headers/contentdispositionheadervalue/tryparse/
---
## ContentDispositionHeaderValue::TryParse(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [ContentDispositionHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::ContentDispositionHeaderValue::TryParse(String input, System::SharedPtr<ContentDispositionHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentDispositionHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ContentDispositionHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)