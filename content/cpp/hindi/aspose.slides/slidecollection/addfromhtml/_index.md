---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API संदर्भ
description: HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।
type: docs
weight: 196
url: /hi/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि

HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स।

## SlideCollection::AddFromHtml(System::String) विधि

HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि

HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग होगा। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स।

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) विधि

HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग होगा। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि

HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग होगा। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स।

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) विधि

HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग होगा। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स
## टिप्पणी

```cpp
// Presentation क्लास की एक इंस्टेंस बनाएं।
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // AddFromHtml मेथड को कॉल करें और HTML फ़ाइल पास करें।
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// फ़ाइल को PowerPoint दस्तावेज़ के रूप में सहेजने के लिए Save मेथड का उपयोग करें।
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## संबंधित

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)