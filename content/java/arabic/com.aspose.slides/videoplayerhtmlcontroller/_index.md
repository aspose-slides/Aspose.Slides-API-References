---
title: VideoPlayerHtmlController
second_title: مرجع API لـ Aspose.Slides للغة Java
description: هذه الفئة تسمح بتصدير ملفات الفيديو والصوت إلى HTML
type: docs
url: /ar/com.aspose.slides/videoplayerhtmlcontroller/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

هذه الفئة تسمح بتصدير ملفات الفيديو والصوت إلى ملف HTML
## المُنشئات

| المنشيء | الوصف |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Creates a new instance of controller |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```

Creates a new instance of controller

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | المسار الذي سيتم إنشاء ملفات الفيديو والصوت فيه |
| fileName | java.lang.String | اسم ملف HTML |
| baseUri | java.lang.String | عنوان URI الأساسي الذي سيُستخدم لإنشاء الروابط |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

يتم استدعاؤه لكتابة رأس مستند html. يتم استدعاؤه مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

يتم استدعاؤه لكتابة تذييل مستند html. يتم استدعاؤه مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

يتم استدعاؤه لكتابة رأس شريحة html. يتم استدعاؤه مرة واحدة لكل شريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

يتم استدعاؤه لكتابة تذييل شريحة html. يتم استدعاؤه مرة واحدة لكل شريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

يتم استدعاؤه قبل رسم الشكل. يتم استدعاؤه مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى generator، سيُنهى توليد صورة الشريحة الحالية، يُدرج جزء html المضاف، وتُبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

يتم استدعاؤه قبل رسم الشكل. يتم استدعاؤه مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى generator، سيُنهى توليد صورة الشريحة الحالية، يُدرج جزء html المضاف، وتُبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```

يتم استدعاؤها قبل تحويل الشكل إلى SVG للسماح للمستخدم بالتحكم في SVG الناتج.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

يحدد المكان الذي يجب تخزين الكائن فيه. تُستدعى هذه الطريقة مرة واحدة لكل معرف كائن. لا يُضمن عدم وجود كائنين ببيانات، semanticName وcontentType متطابقة ولكن بمعرف مختلف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**القيمة المرجعة:**
int

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```

يرجع عنوان URL إلى كائن خارجي. تُستدعى هذه الطريقة دائمًا إذا \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) أرجعت [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) وقد تُستدعى إذا \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) أرجعت [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) لكن الإدراج غير ممكن. يمكن استدعاؤها عدة مرات لنفس معرف الكائن.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**القيمة المرجعة:**
java.lang.String

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```

يحفظ الكائن الخارجي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |