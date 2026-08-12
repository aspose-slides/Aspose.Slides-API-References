---
title: GetRangeItemListLength()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट स्थिति से पास किए गए स्ट्रिंग को RangeItemHeaderValue-class के उदाहरणों के संग्रह में परिवर्तित करता है।
type: docs
weight: 79
url: /hi/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) मेथड

निर्दिष्ट स्थिति से पास किए गए स्ट्रिंग को RangeItemHeaderValue-class के उदाहरणों के संग्रह में परिवर्तित करता है।

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए स्ट्रिंग। |
| startIndex | **int32_t** | पार्स करने के लिए प्रारंभिक स्थिति। |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | एक उदाहरण जहाँ पार्स किया गया संग्रह सौंपा जाएगा। |

### वापसी मान

पार्स किए गए उपस्ट्रिंग की लंबाई, अन्यथा 0।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)