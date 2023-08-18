---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the MediaTypeHeaderValue class.
type: docs
weight: 131
url: /system.net.http.headers/mediatypeheadervalue/tryparse/
---
## MediaTypeHeaderValue::TryParse(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [MediaTypeHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::MediaTypeHeaderValue::TryParse(String input, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)