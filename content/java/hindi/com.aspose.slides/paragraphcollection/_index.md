---
title: ParagraphCollection
second_title: Aspose.Slides for Java API संदर्भ
description: पैराग्राफ़ों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/paragraphcollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

एक पैराग्राफ़ का संग्रह प्रस्तुत करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में वास्तविक रूप से सम्मिलित तत्वों की संख्या प्राप्त करता है। |
| [isReadOnly()](#isReadOnly--) | एक मान प्राप्त करता है जो इंगित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | संग्रह के अंत में एक Paragraph जोड़ता है। |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | संग्रह के अंत में ParagraphCollection की सामग्री जोड़ता है। |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | List में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | निर्दिष्ट इंडेक्स पर संग्रह में एक Paragraph सम्मिलित करता है। |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | निर्दिष्ट इंडेक्स पर संग्रह में ParagraphCollection की सामग्री सम्मिलित करता है। |
| [clear()](#clear--) | संग्रह से सभी तत्व हटाता है। |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं। |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, विशेष Array इंडेक्स से शुरू होते हुए। |
| [removeAt(int index)](#removeAt-int-) | संग्रह के निर्दिष्ट इंडेक्स पर तत्व हटाता है। |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से किसी विशिष्ट वस्तु की पहली उपस्थिती हटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से इटरिट करता है। |
| [iteratorJava()](#iteratorJava--) | संपूर्ण संग्रह के लिए एक java iterator लौटाता है। |
| [getSlide()](#getSlide--) | पैराग्राफ़ संग्रह की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | पैराग्राफ़ संग्रह की पैरेंट प्रस्तुति लौटाता है। |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है। |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है। |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | निर्दिष्ट पैराग्राफ़ को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है। |
### getCount() {#getCount--}
```
public final int getCount()
```


संग्रह में वास्तविक रूप से सम्मिलित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


एक मान प्राप्त करता है जो इंगित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean - true अगर [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है; अन्यथा false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```


निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```


संग्रह के अंत में एक Paragraph जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | संग्रह के अंत में जोड़ने के लिए Paragraph। |
### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```


संग्रह के अंत में ParagraphCollection की सामग्री जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | संग्रह के अंत में जोड़ने के लिए ParagraphCollection। |

**वापसी:**
int - वह इंडेक्स जहाँ Paragraph जोड़ा गया या -1 यदि जोड़ने के लिए कुछ नहीं है।
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```


List में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | List में लोकेट करने के लिए ऑब्जेक्ट। |

**वापसी:**
int - यदि आइटम सूची में मिला तो उसका इंडेक्स; अन्यथा -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```


निर्दिष्ट इंडेक्स पर संग्रह में एक Paragraph सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित इंडेक्स जहाँ Paragraph सम्मिलित किया जाना चाहिए। |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | सम्मिलित करने के लिए Paragraph। |
### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```


निर्दिष्ट इंडेक्स पर संग्रह में ParagraphCollection की सामग्री सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित इंडेक्स जहाँ पैराग्राफ़ सम्मिलित किए जाने चाहिए। |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | सम्मिलित करने के लिए पैराग्राफ़। |
### clear() {#clear--}
```
public final void clear()
```


संग्रह से सभी तत्व हटाता है।
### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजने के लिए ऑब्जेक्ट। |

**वापसी:**
boolean - true अगर आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में मिला; अन्यथा false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, विशेष Array इंडेक्स से शुरू होते हुए।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | वह एक-आयामी Array जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का लक्ष्य है। Array में शून्य-आधारित इंडेक्सिंग होनी चाहिए। |
| arrayIndex | int | वह शून्य-आधारित इंडेक्स जहाँ कॉपी शुरू होता है। |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


संग्रह के निर्दिष्ट इंडेक्स पर तत्व हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित इंडेक्स। |
### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिती हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाने के लिए ऑब्जेक्ट। |

**वापसी:**
boolean - true अगर आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) से सफलतापूर्वक हटाया गया; अन्यथा false। यदि आइटम मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में नहीं मिला तो भी false लौटाता है।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```


एक enumerator लौटाता है जो संग्रह के माध्यम से इटरिट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - एक IGenericEnumerator जिसे संग्रह के माध्यम से इटरिट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```


संपूर्ण संग्रह के लिए एक java iterator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - एक java.util.Iterator संपूर्ण संग्रह के लिए।
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


पैराग्राफ़ संग्रह की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


पैराग्राफ़ संग्रह की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```


निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | HTML टेक्स्ट। |
### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | HTML टेक्स्ट। |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | वह resolver कॉलबैक ऑब्जेक्ट जो URIs को रिजॉल्व करता है और संदर्भित ऑब्जेक्ट्स को फ़ेच करता है। |
| uri | java.lang.String | HTML दस्तावेज़ जोड़ने के लिए URI। रिलेटिव लिंक को रिजॉल्व करने के लिए प्रयोग होता है।

--------------------

Resolver निर्दिष्ट करने से संभावित रूप से एक कमजोरी उत्पन्न हो सकती है। सावधानी से उपयोग करें। |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


निर्दिष्ट पैराग्राफ़ को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| firstParagraphIndex | int | पहला पैराग्राफ़ इंडेक्स। |
| paragraphsCount | int | पैराग्राफ़ गिनती। |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | रूपांतरण विकल्प [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)। |

**वापसी:**
java.lang.String - उत्पन्न HTML।