---
title: ToString()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: "इस उदाहरण के मान को निर्दिष्ट सांस्कृतिक-विशिष्ट स्वरूपण जानकारी का उपयोग करके समतुल्य System::String में परिवर्तित करता है।"
type: docs
weight: 196
url: /hi/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) विधि


इस उदाहरण के मान को निर्दिष्ट सांस्कृतिक-विशिष्ट स्वरूपण जानकारी का उपयोग करके समतुल्य [System::String](../../string/) में परिवर्तित करता है।

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | एक [System::IFormatProvider](../../iformatprovider/) इंटरफ़ेस कार्यान्वयन जो सांस्कृतिक-विशिष्ट स्वरूपण जानकारी प्रदान करता है। |

### वापसी मान

एक [System::String](../../string/) उदाहरण जो इस उदाहरण के मान के समतुल्य है।

## IConvertible::ToString() const विधि


C# [Object.ToString()](../../object/tostring/) मेथड का समरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने में सक्षम बनाता है।

```cpp
virtual String System::Object::ToString() const
```


### वापसी मान

[String](../../string/) प्रतिनिधित्व जैसा कि अंतिम क्लास द्वारा प्रदान किया गया है।

## देखें

* टाइपडिफ़ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [IConvertible](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)