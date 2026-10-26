---
title: IParagraphCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक पैराग्राफ़ के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**  
सभी लागू इंटरफ़ेस:
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Represents a collection of a paragraphs.  
एक पैराग्राफ़ के संग्रह का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तविक रूप से सम्मिलित तत्वों की संख्या प्राप्त करता है। |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | संग्रह के अंत में एक Paragraph जोड़ता है। |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | संग्रह के अंत में ParagraphCollection की सामग्री जोड़ता है। |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | निर्दिष्ट अनुक्रमणिका पर संग्रह में एक Paragraph सम्मिलित करता है। |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | निर्दिष्ट अनुक्रमणिका पर संग्रह में ParagraphCollection की सामग्री सम्मिलित करता है। |
| [clear()](#clear--) | संग्रह से सभी तत्व हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमणिका पर तत्व हटाता है। |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | विशिष्ट पैराग्राफ का पहला प्रकट होना हटाता है। |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है। |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है। |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | निर्दिष्ट पैराग्राफ को HTML में बदलता है और इसे String ऑब्जेक्ट के रूप में लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IParagraph](../../com.aspose.slides/iparagraph)

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में वास्तविक रूप से सम्मिलित तत्वों की संख्या प्राप्त करता है। Read-only int.

**वापसी:**
int

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

संग्रह के अंत में एक Paragraph जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | संग्रह के अंत में जोड़ा जाने वाला Paragraph। |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

संग्रह के अंत में ParagraphCollection की सामग्री जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | संग्रह के अंत में जोड़ी जाने वाली ParagraphCollection। |

**वापसी:**
int - वह अनुक्रमणिका जिस पर Paragraph जोड़ा गया है या -1 यदि जोड़ने के लिए कुछ नहीं है।

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

संग्रह में निर्दिष्ट अनुक्रमणिका पर एक Paragraph सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित अनुक्रमणिका जहाँ Paragraph सम्मिलित किया जाना चाहिए। |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | सम्मावेशित करने हेतु Paragraph। |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

संग्रह में निर्दिष्ट अनुक्रमणिका पर ParagraphCollection की सामग्री सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित अनुक्रमणिका जहाँ पैराग्राफ़ सम्मिलित किए जाने हैं। |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | सम्मावेशित करने हेतु पैराग्राफ़। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्व हटाता है।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमणिका पर तत्व हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए तत्व की शून्य-आधारित अनुक्रमणिका। |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

विशिष्ट पैराग्राफ का पहला प्रकट होना हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | संग्रह से हटाए जाने वाला पैराग्राफ। |

**वापसी:**
boolean - true यदि वस्तु सफलतापूर्वक हटाई गई; अन्यथा false।

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | HTML पाठ। |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | HTML पाठ। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver कॉलबैक ऑब्जेक्ट जो URIs को हल करता है और संदर्भित वस्तुओं को प्राप्त करता है। |
| uri | java.lang.String | HTML दस्तावेज़ जोड़ने के लिए URI। सापेक्ष लिंक को हल करने में उपयोग किया जाता है। |

--------------------
Resolver को निर्दिष्ट करना संभावित रूप से एक कमजोरी पेश कर सकता है। सावधानी से उपयोग करें।

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

निर्दिष्ट पैराग्राफ को HTML में बदलता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstParagraphIndex | int | पहले पैराग्राफ़ की अनुक्रमणिका int |
| paragraphsCount | int | पैराग्राफ़ संख्या int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | रूपांतरण विकल्प [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**वापसी:**
java.lang.String - उत्पन्न किया गया HTML।