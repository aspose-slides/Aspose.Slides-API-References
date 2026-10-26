---
title: InsertFromHtml
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।
type: docs
weight: 140
url: /hi/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlText | String | जोड़ने के लिए HTML। |
| resolver | IExternalResourceResolver | एक कॉलबैक ऑब्जेक्ट जिसका उपयोग बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न मान

जोड़ी गई स्लाइड्स।

### संबंधित

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlText | String | जोड़ने के लिए HTML। |
| resolver | IExternalResourceResolver | एक कॉलबैक ऑब्जेक्ट जिसका उपयोग बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | Boolean | यह फ़्लैग इन्सर्शन शुरू करने के तरीके को निर्धारित करता है: नई स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true** है, तो डेटा इन्सर्शन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़ी गई स्लाइड्स।

### संबंधित

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlText | String | जोड़ने के लिए HTML। |

### रिटर्न मान

जोड़ी गई स्लाइड्स

### संबंधित

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlText | String | जोड़ने के लिए HTML। |
| useSlideWithIndexAsStart | Boolean | यह फ़्लैग इन्सर्शन शुरू करने के तरीके को निर्धारित करता है: नई स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true** है, तो डेटा इन्सर्शन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़ी गई स्लाइड्स

### संबंधित

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlReader | TextReader | एक TextReader ऑब्जेक्ट जिसका उपयोग HTML फ़ाइल के स्रोत के रूप में किया जाएगा। |
| resolver | IExternalResourceResolver | एक कॉलबैक ऑब्जेक्ट जिसका उपयोग बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न मान

जोड़ी गई स्लाइड्स।

### संबंधित

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlReader | TextReader | एक TextReader ऑब्जेक्ट जिसका उपयोग HTML फ़ाइल के स्रोत के रूप में किया जाएगा। |

### रिटर्न मान

जोड़ी गई स्लाइड्स

### संबंधित

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlStream | Stream | एक Stream ऑब्जेक्ट जिसका उपयोग HTML फ़ाइल के स्रोत के रूप में किया जाएगा। |
| resolver | IExternalResourceResolver | एक कॉलबैक ऑब्जेक्ट जिसका उपयोग बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न मान

जोड़ी गई स्लाइड्स।

### संबंधित

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlStream | Stream | एक Stream ऑब्जेक्ट जिसका उपयोग HTML फ़ाइल के स्रोत के रूप में किया जाएगा। |
| resolver | IExternalResourceResolver | एक कॉलबैक ऑब्जेक्ट जिसका उपयोग बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए किया जाता है। यदि यह पैरामीटर null है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | String | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |
| useSlideWithIndexAsStart | Boolean | यह फ़्लैग इन्सर्शन शुरू करने के तरीके को निर्धारित करता है: नई स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true** है, तो डेटा इन्सर्शन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़ी गई स्लाइड्स।

### संबंधित

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlStream | Stream | एक Stream ऑब्जेक्ट जिसका उपयोग HTML फ़ाइल के स्रोत के रूप में किया जाएगा। |

### रिटर्न मान

जोड़ी गई स्लाइड्स

### संबंधित

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | इन्सर्ट करने की स्थिति। |
| htmlStream | Stream | एक Stream ऑब्जेक्ट जिसका उपयोग HTML फ़ाइल के स्रोत के रूप में किया जाएगा। |
| useSlideWithIndexAsStart | Boolean | यह फ़्लैग इन्सर्शन शुरू करने के तरीके को निर्धारित करता है: नई स्लाइड से या निर्दिष्ट इंडेक्स वाले स्लाइड से। यदि **true** है, तो डेटा इन्सर्शन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा। यदि **false** है, तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |

### रिटर्न मान

जोड़ी गई स्लाइड्स

### संबंधित

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->