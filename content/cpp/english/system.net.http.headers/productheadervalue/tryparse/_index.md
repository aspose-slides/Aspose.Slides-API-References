---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the ProductHeaderValue class.
type: docs
weight: 92
url: /system.net.http.headers/productheadervalue/tryparse/
---
## ProductHeaderValue::TryParse(String, System::SharedPtr\<ProductHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [ProductHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::ProductHeaderValue::TryParse(String input, System::SharedPtr<ProductHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ProductHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)