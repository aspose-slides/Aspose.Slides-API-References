---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the EntityTagHeaderValue class.
type: docs
weight: 105
url: /system.net.http.headers/entitytagheadervalue/tryparse/
---
## EntityTagHeaderValue::TryParse(String, System::SharedPtr\<EntityTagHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [EntityTagHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::EntityTagHeaderValue::TryParse(String input, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [EntityTagHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)