---
title: GetNameValueListLength()
second_title: Aspose.Slides for C++ API संदर्भ
description: पास किए गए स्ट्रिंग को निर्दिष्ट सूचकांक से NameValueHeaderValue-class के इंस्टेंस की संग्रह में परिवर्तित करता है और पार्स किए गए उपस्ट्रिंग की लंबाई लौटाता है।
type: docs
weight: 131
url: /hi/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) विधि

विशिष्ट सूचकांक से पास किए गए स्ट्रिंग को NameValueHeaderValue-class के इंस्टेंस की संग्रह में परिवर्तित करता है और पार्स किए गए उपस्ट्रिंग की लंबाई लौटाता है।

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | विश्लेषण करने के लिए एक स्ट्रिंग। |
| startIndex | **int32_t** | विश्लेषण के लिए प्रारंभ स्थिति। |
| delimiter | char16_t | निर्दिष्ट स्ट्रिंग में आइटम को अलग करने के लिए उपयोग की जाने वाली स्ट्रिंग। |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | आउटपुट पैरामीटर जहाँ एक पार्स किया गया संग्रह आवंटित किया जाएगा। |

### वापसी मान

पार्स किए गए उपस्ट्रिंग की लंबाई।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ObjectCollection](../../objectcollection/)
* क्लास [NameValueHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)