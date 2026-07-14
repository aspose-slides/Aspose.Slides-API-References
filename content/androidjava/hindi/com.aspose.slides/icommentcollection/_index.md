---
title: ICommentCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक लेखक की टिप्पणियों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icommentcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

एक लेखक की टिप्पणियों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | संग्रह के अंत में नई टिप्पणी जोड़ता है। |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | संग्रह के अंत में नई आधुनिक टिप्पणी जोड़ता है। |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | निर्दिष्ट सूचकांक पर संग्रह में नई टिप्पणी सम्मिलित करता है। |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | निर्दिष्ट सूचकांक पर संग्रह में नई आधुनिक टिप्पणी सम्मिलित करता है। |
| [toArray()](#toArray--) | सभी टिप्पणियों की एक ऐरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा से सभी टिप्पणियों की एक ऐरे बनाता और लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट सूचकांक पर तत्व हटाता है। |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | संग्रह में निर्दिष्ट टिप्पणी की पहली आवृत्ति हटाता है। |
| [clear()](#clear--) | संग्रह से सभी टिप्पणियों को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IComment](../../com.aspose.slides/icomment)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

संग्रह के अंत में नई टिप्पणी जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नई टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई टिप्पणी जोड़ी जानी है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | टिप्पणी के निर्माण का समय। |

**रिटर्न:**
[IComment](../../com.aspose.slides/icomment) - जोड़ी गई टिप्पणी।
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

संग्रह के अंत में नई आधुनिक टिप्पणी जोड़ता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नई आधुनिक टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| shape | [IShape](../../com.aspose.slides/ishape) | स्लाइड पर वह आकार जिससे नई आधुनिक टिप्पणी जुड़ी होती है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | आधुनिक टिप्पणी के निर्माण का समय। |

**रिटर्न:**
[IModernComment](../../com.aspose.slides/imoderncomment) - जोड़ी गई आधुनिक टिप्पणी।
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

निर्दिष्ट सूचकांक पर संग्रह में नई टिप्पणी सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में उस तत्व का सूचकांक जहाँ टिप्पणी सम्मिलित की जानी है। |
| text | java.lang.String | नई टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई टिप्पणी जोड़ी जानी है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | टिप्पणी के निर्माण का समय। |

**रिटर्न:**
[IComment](../../com.aspose.slides/icomment) - सम्मिलित टिप्पणी।
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

निर्दिष्ट सूचकांक पर संग्रह में नई आधुनिक टिप्पणी सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में उस तत्व का सूचकांक जहाँ आधुनिक टिप्पणी सम्मिलित की जानी है। |
| text | java.lang.String | नई आधुनिक टिप्पणी का साधारण पाठ। |
| slide | [ISlide](../../com.aspose.slides/islide) | प्रस्तुति में वह स्लाइड जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| shape | [IShape](../../com.aspose.slides/ishape) | स्लाइड पर वह आकार जिससे नई आधुनिक टिप्पणी जुड़ी होती है। |
| position | android.graphics.PointF | स्लाइड पर वह स्थिति जहाँ नई आधुनिक टिप्पणी जोड़ी जानी है। |
| creationTime | java.util.Date | आधुनिक टिप्पणी के निर्माण का समय। |

**रिटर्न:**
[IModernComment](../../com.aspose.slides/imoderncomment) - सम्मिलित आधुनिक टिप्पणी।
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

सभी टिप्पणियों की एक ऐरे बनाता और लौटाता है।

**रिटर्न:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) की ऐरे।
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

निर्दिष्ट सीमा से सभी टिप्पणियों की एक ऐरे बनाता और लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | पहली लौटाई जाने वाली टिप्पणी का सूचकांक। |
| count | int | लौटाए जाने वाले टिप्पणियों की संख्या। |

**रिटर्न:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) की ऐरे।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर तत्व हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित सूचकांक। |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

संग्रह में निर्दिष्ट टिप्पणी की पहली आवृत्ति हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | संग्रह से हटाने के लिए टिप्पणी। |
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी टिप्पणियों को हटाता है।