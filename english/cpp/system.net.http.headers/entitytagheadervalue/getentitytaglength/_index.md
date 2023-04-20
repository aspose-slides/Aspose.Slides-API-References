---
title: GetEntityTagLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the EntityTagHeaderValue class.
type: docs
weight: 118
url: /cpp/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [EntityTagHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

The length of a parsed substring, otherwise 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [EntityTagHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)