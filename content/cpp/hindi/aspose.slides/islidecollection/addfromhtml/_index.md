---
title: AddFromHtml()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।
type: docs
weight: 144
url: /hi/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि


HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिये Html। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुएँ प्राप्त करने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। रिलेटिव लिंक के समाधान के लिये उपयोग किया जाता है। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स।

## ISlideCollection::AddFromHtml(System::String) विधि


HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिये Html। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि


HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader ऑब्जेक्ट जो HTML फ़ाइल का स्रोत के रूप में उपयोग किया जाएगा। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुएँ प्राप्त करने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। रिलेटिव लिंक के समाधान के लिये उपयोग किया जाता है। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स।

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) विधि


HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader ऑब्जेक्ट जो HTML फ़ाइल का स्रोत के रूप में उपयोग किया जाएगा। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि


HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक Stream ऑब्जेक्ट जो HTML फ़ाइल का स्रोत के रूप में उपयोग किया जाएगा। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुएँ प्राप्त करने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। रिलेटिव लिंक के समाधान के लिये उपयोग किया जाता है। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स।

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) विधि


HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक Stream ऑब्जेक्ट जो HTML फ़ाइल का स्रोत के रूप में उपयोग किया जाएगा। |

### रिटर्न वैल्यू

जोड़े गए स्लाइड्स

## देखें भी

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)