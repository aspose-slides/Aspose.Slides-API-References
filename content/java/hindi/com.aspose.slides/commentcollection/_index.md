---
title: CommentCollection
second_title: Aspose.Slides for Java API संदर्भ
description: एक लेखक की टिप्पणियों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/commentcollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

एक लेखक के सभी टिप्पणियों का संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | संग्रह के अंत में नई टिप्पणी जोड़ें। |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | संग्रह के अंत में नई आधुनिक टिप्पणी जोड़ें। |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | निर्दिष्ट अनुक्रमांक पर संग्रह में नई टिप्पणी डालें। |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | निर्दिष्ट अनुक्रमांक पर संग्रह में नई आधुनिक टिप्पणी डालें। |
| [toArray()](#toArray--) | सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा से सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व हटाता है। |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | संग्रह में निर्दिष्ट टिप्पणी की पहली आवृत्ति हटाता है। |
| [clear()](#clear--) | संग्रह से सभी टिप्पणियाँ हटाता है। |
| [iterator()](#iterator--) | एक इटेरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है। |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | अनुक्रमांक द्वारा संग्रह में टिप्पणी खोजता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह के सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुँच समकालिक (थ्रेड-सुरक्षित) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण मूल लौटाता है। |
### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य  int .

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [Comment](../../com.aspose.slides/comment).

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

एक संग्रह के अंत में नई टिप्पणी जोड़ें।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | नई टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई टिप्पणी जोड़ी जानी है। |
| position | java.awt.geom.Point2D.Float | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | टिप्पणी निर्माण का समय। |

**रिटर्न:**
[IComment](../../com.aspose.slides/icomment) - जोड़ी गई टिप्पणी।
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

एक संग्रह के अंत में नई आधुनिक टिप्पणी जोड़ें।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | नई आधुनिक टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| shape | [IShape](../../com.aspose.slides/ishape) | स्लाइड पर वह आकृति जिससे नई आधुनिक टिप्पणी जुड़ी है। |
| position | java.awt.geom.Point2D.Float | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | आधुनिक टिप्पणी निर्माण का समय। |

**रिटर्न:**
[IModernComment](../../com.aspose.slides/imoderncomment) - जोड़ी गई आधुनिक टिप्पणी।
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में नई टिप्पणी डालें।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | वह अनुक्रमांक जहाँ टिप्पणी डालनी है। |
| text | java.lang.String | नई टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई टिप्पणी जोड़ी जानी है। |
| position | java.awt.geom.Point2D.Float | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | टिप्पणी निर्माण का समय। |

**रिटर्न:**
[IComment](../../com.aspose.slides/icomment) - डाली गई टिप्पणी।
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में नई आधुनिक टिप्पणी डालें।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | वह अनुक्रमांक जहाँ नई आधुनिक टिप्पणी डालनी है। |
| text | java.lang.String | नई आधुनिक टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| shape | [IShape](../../com.aspose.slides/ishape) | स्लाइड पर वह आकृति जिससे नई आधुनिक टिप्पणी जुड़ी है। |
| position | java.awt.geom.Point2D.Float | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | आधुनिक टिप्पणी निर्माण का समय। |

**रिटर्न:**
[IModernComment](../../com.aspose.slides/imoderncomment) - डाली गई आधुनिक टिप्पणी।
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है।

**रिटर्न:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) का ऐरे।
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

निर्दिष्ट सीमा से सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | पहला टिप्पणी का अनुक्रमांक जिसे लौटाना है। |
| count | int | लौटाने के लिए टिप्पणियों की संख्या। |

**रिटर्न:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) का ऐरे।
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व हटाता है।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | हटाने के लिए तत्व का शून्य-आधारित अनुक्रमांक। |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

संग्रह में निर्दिष्ट टिप्पणी की पहली आवृत्ति हटाता है।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | संग्रह से हटाने वाली टिप्पणी। |

### clear() {#clear--}
```
public final void clear()
```

सभी टिप्पणियाँ हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

एक इटेरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - संग्रह को इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

एक जावा इटेरेटर लौटाता है जो पूरे संग्रह के लिए है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - पूरे संग्रह के लिए java.util.Iterator।
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

अनुक्रमांक द्वारा संग्रह में टिप्पणी खोजता है।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| idx | int | खोजे जाने वाली टिप्पणी का यूनिक इंडेक्स  int . |

**रिटर्न:**
[IComment](../../com.aspose.slides/icomment) - मिला हुआ टिप्पणी या शून्य [IComment](../../com.aspose.slides/icomment)।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह के सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुँच समकालिक (थ्रेड-सुरक्षित) है। केवल-पढ़ने योग्य  boolean .

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण मूल लौटाता है। केवल-पढ़ने योग्य  Object .

**रिटर्न:**
java.lang.Object