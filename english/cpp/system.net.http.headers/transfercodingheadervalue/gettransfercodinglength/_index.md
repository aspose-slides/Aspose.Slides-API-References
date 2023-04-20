---
title: GetTransferCodingLength()
second_title: Aspose.Slides for C++ API Reference
description: Converts a passed string from the specified index to an instance of the TransferCodingHeaderValue class.
type: docs
weight: 105
url: /cpp/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) method


Converts a passed string from the specified index to an instance of the [TransferCodingHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A string to parse. |
| startIndex | **int32_t** | A start position for parsing. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | An instance where a parsed object will be assigned. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | The delegate that is used to create instances of the [TransferCodingHeaderValue](../) class. |

### Return Value

Returns the length of a parsed substring, otherwise 0.

## See Also

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)