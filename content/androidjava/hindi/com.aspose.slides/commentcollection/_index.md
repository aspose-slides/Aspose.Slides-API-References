---
title: CommentCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक लेखक की टिप्पणियों का संग्रह दर्शाता है।
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

एक लेखक की टिप्पणियों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | संग्रह के अंत में नई टिप्पणी जोड़ें। |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | संग्रह के अंत में नई आधुनिक टिप्पणी जोड़ें। |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | निर्दिष्ट अनुक्रमांक पर संग्रह में नई टिप्पणी डालें। |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | निर्दिष्ट अनुक्रमांक पर संग्रह में नई आधुनिक टिप्पणी डालें। |
| [toArray()](#toArray--) | सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा से सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | संग्रह में निर्दिष्ट टिप्पणी की पहली घटना को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी टिप्पणियों को हटाता है। |
| [iterator()](#iterator--) | एक एन्क्यूमेरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटरेटर लौटाता है। |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | अनुक्रमांक द्वारा संग्रह में टिप्पणी ढूँढ़ता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्व संग्रह से निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाता है कि क्या संग्रह की पहुंच समकालित (थ्रेड-सेफ़) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालन मूल लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य  int .

**वापसी:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [Comment](../../com.aspose.slides/comment)।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

संग्रह के अंत में नई टिप्पणी जोड़ें।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | नई टिप्पणी का साधारण टेक्स्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई टिप्पणी जोड़ी जानी है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | टिप्पणी बनाने का समय। |

**वापसी:**  
[IComment](../../com.aspose.slides/icomment) - जोड़ी गई टिप्पणी।

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

संग्रह के अंत में नई आधुनिक टिप्पणी जोड़ें।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | नई आधुनिक टिप्पणी का साधारण टेक्स्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| shape | [IShape](../../com.aspose.slides/ishape) | स्लाइड पर वह आकृति जिससे नई आधुनिक टिप्पणी जुड़ी है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | आधुनिक टिप्पणी बनाने का समय। |

**वापसी:**  
[IModernComment](../../com.aspose.slides/imoderncomment) - जोड़ी गई आधुनिक टिप्पणी।

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में नई टिप्पणी डालें।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | वह अनुक्रमांक जहाँ टिप्पणी डाली जानी है। |
| text | java.lang.String | नई टिप्पणी का साधारण टेक्स्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई टिप्पणी जोड़ी जानी है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | टिप्पणी बनाने का समय। |

**वापसी:**  
[IComment](../../com.aspose.slides/icomment) - डाली गई टिप्पणी।

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में नई आधुनिक टिप्पणी डालें।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | वह अनुक्रमांक जहाँ आधुनिक टिप्पणी डाली जानी है। |
| text | java.lang.String | नई आधुनिक टिप्पणी का साधारण टेक्स्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| shape | [IShape](../../com.aspose.slides/ishape) | स्लाइड पर वह आकृति जिससे नई आधुनिक टिप्पणी जुड़ी है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | आधुनिक टिप्पणी बनाने का समय। |

**वापसी:**  
[IModernComment](../../com.aspose.slides/imoderncomment) - डाली गई आधुनिक टिप्पणी।

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है।

**वापसी:**  
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) का ऐरे।

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

निर्दिष्ट सीमा से सभी टिप्पणियों के साथ एक ऐरे बनाता और लौटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| startIndex | int | पहला टिप्पणी का अनुक्रमांक जिसे लौटाना है। |
| count | int | लौटाई जाने वाली टिप्पणियों की संख्या। |

**वापसी:**  
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) का ऐरे।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

संग्रह में निर्दिष्ट टिप्पणी की पहली घटना को हटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | संग्रह से हटाने के लिए टिप्पणी। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी टिप्पणियों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

एक एन्क्यूमेरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - संग्रह को इटररेट करने के लिए उपयोगी IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

पूरे संग्रह के लिए एक java इटरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - पूरे संग्रह के लिए java.util.Iterator।

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

अनुक्रमांक द्वारा संग्रह में टिप्पणी ढूँढ़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| idx | int | खोजी जाने वाली टिप्पणी का अद्वितीय अनुक्रमांक  int । |

**वापसी:**  
[IComment](../../com.aspose.slides/icomment) - पायी गई टिप्पणी या null [IComment](../../com.aspose.slides/icomment)।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुंच समकालित (थ्रेड-सेफ़) है। केवल-पढ़ने योग्य  boolean ।

**वापसी:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालन मूल लौटाता है। केवल-पढ़ने योग्य  Object 。

**वापसी:**  
java.lang.Object