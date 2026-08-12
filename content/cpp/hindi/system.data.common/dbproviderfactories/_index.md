---
title: DbProviderFactories
second_title: Aspose.Slides for C++ API संदर्भ
description: "DB प्रोवाइडर फ़ैक्ट्रीज़ प्राप्त करने के लिए API। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन त्रुटियों का कारण बन सकता है। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 53
url: /hi/system.data.common/dbproviderfactories/
---
## DbProviderFactories वर्ग

DB प्रोवाइडर फ़ैक्टरीज प्राप्त करने के लिए API। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ उत्पन्न होंगी। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
class DbProviderFactories
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | नाम द्वारा DB प्रोवाइडर फ़ैक्ट्री प्राप्त करता है। |

## देखें

* नामस्थान [System::Data::Common](../)
* लाइब्रेरी [Aspose.Slides](../../)