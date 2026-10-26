---
title: GetTransferCodingLength()
second_title: Aspose.Slides for C++ API संदर्भ
description: पास किए गए स्ट्रिंग को निर्दिष्ट सूचकांक से TransferCodingHeaderValue क्लास के एक इंस्टेंस में परिवर्तित करता है।
type: docs
weight: 105
url: /hi/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) method

पास किए गए स्ट्रिंग को निर्दिष्ट इंडेक्स से [TransferCodingHeaderValue](../) क्लास के एक इंस्टेंस में परिवर्तित करता है।

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए एक स्ट्रिंग। |
| startIndex | **int32_t** | पार्स करने के लिए प्रारंभिक स्थिति। |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | वह इंस्टेंस जहाँ पार्स किया हुआ ऑब्जेक्ट असाइन किया जाएगा। |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | वह डेलीगेट जो [TransferCodingHeaderValue](../) क्लास के इंस्टेंस बनाने के लिए उपयोग किया जाता है। |

### Return Value

पार्स किए गए उपस्ट्रिंग की लंबाई लौटाता है, अन्यथा 0।

## See Also

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)