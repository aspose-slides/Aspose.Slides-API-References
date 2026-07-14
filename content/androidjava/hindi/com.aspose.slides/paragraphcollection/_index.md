---
title: ParagraphCollection
second_title: Aspose.Slides for Android के लिये Java API रेफरेंस
description: पैराग्राफ़ का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/paragraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

एक Paragraphs का संग्रह दर्शाता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [isReadOnly()](#isReadOnly--) | यह दर्शाने वाला मान प्राप्त करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल पढ़ने योग्य है या नहीं। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | संग्रह के अंत में एक Paragraph जोड़ता है। |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | संग्रह के अंत में ParagraphCollection की सामग्री जोड़ता है। |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | सूची में किसी विशिष्ट वस्तु का अनुक्रमांक निर्धारित करता है। |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | निर्दिष्ट अनुक्रमांक पर संग्रह में एक Paragraph डालता है। |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | निर्दिष्ट अनुक्रमांक पर संग्रह में ParagraphCollection की सामग्री डालता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं। |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो किसी विशेष Array अनुक्रमांक से शुरू होता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमांक पर संग्रह से तत्व हटाता है। |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | विशिष्ट वस्तु के प्रथम प्रकट को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह को क्रमागत करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिये java iterator लौटाता है। |
| [getSlide()](#getSlide--) | Paragraphs संग्रह की मूल स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | Paragraphs संग्रह की मूल प्रस्तुति लौटाता है। |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है। |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है। |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | निर्दिष्ट Paragraphs को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है। |

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int.

**Returns:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के केवल पढ़ने योग्य होने का मान प्राप्त करता है। केवल पढ़ने योग्य boolean.

**Returns:**
boolean - true यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल पढ़ने योग्य है; अन्यथा, false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

संग्रह के अंत में एक Paragraph जोड़ता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | संग्रह के अंत में जोड़ी जाने वाली Paragraph। |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

संग्रह के अंत में ParagraphCollection की सामग्री जोड़ता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | संग्रह के अंत में जोड़ी जाने वाली ParagraphCollection। |

**Returns:**
int - वह अनुक्रमांक जहाँ Paragraph जोड़ी गई है या कोई तत्व न हो तो -1।

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

सूची में किसी विशिष्ट वस्तु का अनुक्रमांक निर्धारित करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | सूची में खोजी जाने वाली वस्तु। |

**Returns:**
int - सूची में वस्तु का अनुक्रमांक; यदि न मिला हो तो -1।

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में एक Paragraph डालता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमांक जहाँ Paragraph डालना है। |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | डालने के लिये Paragraph। |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में ParagraphCollection की सामग्री डालता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमांक जहाँ Paragraphs डालना है। |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | डालने के लिये Paragraphs। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्वों को हटाता है।

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं, निर्धारित करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजी जाने वाली वस्तु। |

**Returns:**
boolean - true यदि वस्तु [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाई गई; अन्यथा, false।

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो किसी विशेष Array अनुक्रमांक से शुरू होता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | वह एक-आयामी Array जहाँ से [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को कॉपी किया जाएगा। Array को शून्य-आधारित अनुक्रमणिका रखनी चाहिए। |
| arrayIndex | int | Array में वह शून्य-आधारित अनुक्रमांक जहाँ से कॉपी शुरू होगा। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह के निर्दिष्ट अनुक्रमांक पर तत्व हटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) से विशिष्ट वस्तु की प्रथम उपस्थिति हटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाने वाली वस्तु। |

**Returns:**
boolean - true यदि वस्तु [IGenericCollection](../../com.aspose.slides/igenericcollection) से सफलतापूर्वक हटाई गई; अन्यथा, false। यदि वस्तु मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में नहीं पाई गई तो भी यह false लौटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

एक enumerator लौटाता है जो संग्रह को क्रमागत करता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - संग्रह को क्रमागत करने के लिये उपयोगी IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

पूरे संग्रह के लिये java iterator लौटाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - पूरे संग्रह के लिये java.util.Iterator।

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Paragraphs संग्रह की मूल स्लाइड लौटाता है। केवल पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Paragraphs संग्रह की मूल प्रस्तुति लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML पाठ। |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

निर्दिष्ट html स्ट्रिंग से पाठ को संग्रह में जोड़ता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML पाठ। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | वह कॉलबैक ऑब्जेक्ट जो URI को हल करता है और संदर्भित वस्तुओं को प्राप्त करता है। |
| uri | java.lang.String | HTML दस्तावेज़ जोड़ने के लिये URI। सापेक्ष लिंक हल करने में प्रयुक्त।

--------------------

Resolver निर्दिष्ट करने से संभावित रूप से एक असुरक्षा उत्पन्न हो सकती है। सावधानी से उपयोग करें। |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

निर्दिष्ट Paragraphs को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | पहला Paragraph अनुक्रमांक |
| paragraphsCount | int | Paragraphs की संख्या |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | परिवर्तित विकल्प [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Returns:**
java.lang.String - उत्पन्न HTML।