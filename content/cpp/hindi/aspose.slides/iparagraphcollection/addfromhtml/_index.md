---
title: AddFromHtml()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट HTML स्ट्रिंग से पाठ को संग्रह में जोड़ता है।
type: docs
weight: 92
url: /hi/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) विधि


निर्दिष्ट HTML स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML टेक्स्ट। |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि


निर्दिष्ट HTML स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML टेक्स्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | URI को हल करने और संदर्भित वस्तुओं को प्राप्त करने वाला रेज़ॉल्वर कॉलबैक ऑब्जेक्ट। |
| uri | [System::String](../../../system/string/) | HTML दस्तावेज़ जोड़ने के लिए URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
## टिप्पणियाँ



रेज़ॉल्वर निर्दिष्ट करने से संभावित रूप से एक असुरक्षा उत्पन्न हो सकती है। सावधानीपूर्वक उपयोग करें।
## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [IParagraphCollection](../)
* क्लास [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)