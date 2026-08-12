---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ एपीआई रेफ़रेंस
description: HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।
type: docs
weight: 157
url: /hi/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा कर दिया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### वापसी मान

जोड़े गए स्लाइड्स।

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |

### वापसी मान

जोड़े गए स्लाइड्स

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा ऐसा TextReader ऑब्जेक्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा कर दिया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### वापसी मान

जोड़े गए स्लाइड्स।

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा ऐसा TextReader ऑब्जेक्ट। |

### वापसी मान

जोड़े गए स्लाइड्स

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा ऐसा Stream ऑब्जेक्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा कर दिया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### वापसी मान

जोड़े गए स्लाइड्स।

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा ऐसा Stream ऑब्जेक्ट। |

### वापसी मान

जोड़े गए स्लाइड्स

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |
| useSlideWithIndexAsStart | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट सूचकांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट सूचकांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनायी गयी स्लाइडों में जोड़ा जाएगा। |

### वापसी मान

जोड़े गए स्लाइड्स

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlText | [System::String](../../../system/string/) | जोड़ने के लिए HTML। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा कर दिया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट सूचकांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट सूचकांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनायी गयी स्लाइडों में जोड़ा जाएगा। |

### वापसी मान

जोड़े गए स्लाइड्स।

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा ऐसा Stream ऑब्जेक्ट। |
| useSlideWithIndexAsStart | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट सूचकांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट सूचकांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनायी गयी स्लाइडों में जोड़ा जाएगा। |

### वापसी मान

जोड़े गए स्लाइड्स

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | सम्मिलित करने की स्थिति। |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा ऐसा Stream ऑब्जेक्ट। |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा कर दिया जाएगा। |
| uri | [System::String](../../../system/string/) | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट सूचकांक वाली स्लाइड से। यदि **true** है, तो डेटा सम्मिलन निर्दिष्ट सूचकांक वाली स्लाइड के खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनायी गयी स्लाइडों में जोड़ा जाएगा। |

### वापसी मान

जोड़े गए स्लाइड्स।

## देखें

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