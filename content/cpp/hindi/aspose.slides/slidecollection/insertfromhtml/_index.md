---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API संदर्भ
description: HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।
type: docs
weight: 209
url: /hi/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न मान

जोड़े गए स्लाइड्स।

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | **bool** | यह फ्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नए स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true**, तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाले स्लाइड में खाली स्थान से शुरू होगा। यदि **false**, तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़े गए स्लाइड्स।

## SlideCollection::InsertFromHtml(int32_t, System::String) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |

### रिटर्न मान

जोड़े गए स्लाइड्स

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |
| useSlideWithIndexAsStart | **bool** | यह फ्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नए स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true**, तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाले स्लाइड में खाली स्थान से शुरू होगा। यदि **false**, तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़े गए स्लाइड्स

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML फाइल का स्रोत के रूप में उपयोग किया जाने वाला TextReader ऑब्जेक्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न मान

जोड़े गए स्लाइड्स।

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML फाइल का स्रोत के रूप में उपयोग किया जाने वाला TextReader ऑब्जेक्ट। |

### रिटर्न मान

जोड़े गए स्लाइड्स

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फाइल का स्रोत के रूप में उपयोग किया जाने वाला Stream ऑब्जेक्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न मान

जोड़े गए स्लाइड्स।

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फाइल का स्रोत के रूप में उपयोग किया जाने वाला Stream ऑब्जेक्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | **bool** | यह फ्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नए स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true**, तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाले स्लाइड में खाली स्थान से शुरू होगा। यदि **false**, तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़े गए स्लाइड्स।

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फाइल का स्रोत के रूप में उपयोग किया जाने वाला Stream ऑब्जेक्ट। |

### रिटर्न मान

जोड़े गए स्लाइड्स

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) विधि

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थान पर संग्रह में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फाइल का स्रोत के रूप में उपयोग किया जाने वाला Stream ऑब्जेक्ट। |
| useSlideWithIndexAsStart | **bool** | यह फ्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नए स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true**, तो डेटा सम्मिलन निर्दिष्ट इंडेक्स वाले स्लाइड में खाली स्थान से शुरू होगा। यदि **false**, तो डेटा बनाई गई स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़े गए स्लाइड्स

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlide](../../islide/)
* क्लास [String](../../../system/string/)
* क्लास [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* क्लास [SlideCollection](../)
* क्लास [TextReader](../../../system.io/textreader/)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)