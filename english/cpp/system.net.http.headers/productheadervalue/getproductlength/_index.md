---
title: GetProductLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the ProductHeaderValue class.
type: docs
weight: 105
url: /cpp/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [ProductHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

Returns the length of a parsed substring, otherwise 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ProductHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)