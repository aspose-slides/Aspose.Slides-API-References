---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट HTML स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।
type: docs
weight: 157
url: /hi/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) विधि

निर्दिष्ट HTML स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML टेक्स्ट। |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि

निर्दिष्ट HTML स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML टेक्स्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver कॉलबैक ऑब्जेक्ट जो URIs को हल करता है और संदर्भित ऑब्जेक्ट्स को प्राप्त करता है। |
| uri | [System::String](../../../system/string/) | HTML दस्तावेज़ जोड़ने के लिए URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |

## टिप्पणियाँ

Resolver निर्दिष्ट करने से संभावित रूप से एक सुरक्षा कमजोरी उत्पन्न हो सकती है। सावधानी से उपयोग करें।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ParagraphCollection](../)
* क्लास [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)