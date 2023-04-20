---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Trying to convert a passed string to an instance of the AuthenticationHeaderValue class.
type: docs
weight: 105
url: /cpp/system.net.http.headers/authenticationheadervalue/tryparse/
---
## AuthenticationHeaderValue::TryParse(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) method


Trying to convert a passed string to an instance of the [AuthenticationHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::AuthenticationHeaderValue::TryParse(String input, System::SharedPtr<AuthenticationHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[AuthenticationHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [AuthenticationHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)