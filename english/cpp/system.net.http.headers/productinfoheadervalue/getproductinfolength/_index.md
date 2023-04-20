---
title: GetProductInfoLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the ProductInfoHeaderValue class.
type: docs
weight: 105
url: /cpp/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [ProductInfoHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

Returns the length of a parsed substring, otherwise 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ProductInfoHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)