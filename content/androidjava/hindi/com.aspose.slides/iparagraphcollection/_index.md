---
title: IParagraphCollection
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API संदर्भ
description: एक पैराग्राफ़ का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/iparagraphcollection/
---
**सभी लागू इंटरफेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

एक पैराग्राफ का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व को प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | एक Paragraph को संग्रह के अंत में जोड़ता है। |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | ParagraphCollection की सामग्री को संग्रह के अंत में जोड़ता है। |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | निर्दिष्ट अनुक्रमांक पर संग्रह में एक Paragraph डालता है। |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | निर्दिष्ट अनुक्रमांक पर संग्रह में ParagraphCollection की सामग्री डालता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | किसी विशिष्ट पैराग्राफ की पहली उपस्थिति को हटाता है। |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है। |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है। |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | निर्दिष्ट पैराग्राफों को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व को प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

एक Paragraph को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | संग्रह के अंत में जोड़े जाने वाला Paragraph। |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

ParagraphCollection की सामग्री को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | संग्रह के अंत में जोड़े जाने वाला ParagraphCollection। |

**रिटर्न:**
int - वह इंडेक्स जहाँ Paragraph जोड़ा गया है या -1 यदि जोड़ने के लिए कुछ नहीं है।
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में एक Paragraph डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमांक जहाँ Paragraph डालना है। |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | डालने के लिए Paragraph। |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में ParagraphCollection की सामग्री डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमांक जहाँ पैराग्राफ डालना है। |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | डालने के लिए पैराग्राफ। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

किसी विशिष्ट पैराग्राफ की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | संग्रह से हटाने हेतु पैराग्राफ। |

**रिटर्न:**
boolean - true यदि आइटम सफलतापूर्वक हटाया गया; अन्यथा false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | HTML टेक्स्ट। |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | HTML टेक्स्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI को हल करने और संदर्भित ऑब्जेक्ट प्राप्त करने वाला रेज़ॉल्वर कॉलबैक ऑब्जेक्ट। |
| uri | java.lang.String | HTML दस्तावेज़ जोड़ने के लिए URI। सापेक्ष लिंक हल करने के लिए उपयोग किया जाता है।

--------------------

रेज़ॉल्वर निर्दिष्ट करने से संभावित रूप से एक सुरक्षा कमजोरि उत्पन्न हो सकती है। सावधानी से उपयोग करें। |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

निर्दिष्ट पैराग्राफों को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstParagraphIndex | int | पहला पैराग्राफ अनुक्रमांक int |
| paragraphsCount | int | पैराग्राफ संख्या int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | परिवर्तन विकल्प [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**रिटर्न:**
java.lang.String - जेनरेटेड HTML।