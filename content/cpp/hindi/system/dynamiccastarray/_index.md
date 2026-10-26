---
title: DynamicCastArray()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट सरणी के तत्वों को विभिन्न प्रकार में कास्ट करता है।
type: docs
weight: 2991
url: /hi/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) फ़ंक्शन

निर्दिष्ट सरणी के तत्वों को विभिन्न प्रकार में कास्ट करता है।

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| To | निर्दिष्ट सरणी के तत्वों को कास्ट करने के लिए प्रकार |
| From | कास्ट करने वाले तत्वों की सरणी के तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | कास्ट करने वाले तत्वों को समाहित करने वाली सरणी के लिए साझा पॉइंटर |

### वापसी मान

एक पॉइंटर जो **To** प्रकार के तत्वों वाले नए सरणी की ओर इशारा करता है, जो **from** के तत्वों के बराबर है

अप्रचलित
:   पिछली संगतता के लिए जोड़ा गया। इसके बजाय ExplicitCast का उपयोग करें।

## देखें

* Typedef [SharedPtr](../sharedptr/)
* क्लास [Array](../array/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)