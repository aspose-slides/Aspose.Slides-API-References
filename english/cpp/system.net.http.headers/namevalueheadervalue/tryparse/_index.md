---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the NameValueHeaderValue class.
type: docs
weight: 105
url: /cpp/system.net.http.headers/namevalueheadervalue/tryparse/
---
## NameValueHeaderValue::TryParse(String, System::SharedPtr\<NameValueHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [NameValueHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::NameValueHeaderValue::TryParse(String input, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)