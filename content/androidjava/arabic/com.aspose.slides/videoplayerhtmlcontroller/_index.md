---
title: VideoPlayerHtmlController
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: تسمح هذه الفئة بتصدير ملفات الفيديو والصوت إلى HTML
type: docs
url: /ar/com.aspose.slides/videoplayerhtmlcontroller/
---
**الوراثة:**
java.lang.Object

**كل الواجهات المنفذة:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

تسمح هذه الفئة بتصدير ملفات الفيديو والصوت إلى HTML
## المنشئات

| المنشىء | الوصف |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | إنشاء نسخة جديدة من المتحكم |
## الأساليب

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


إنشاء نسخة جديدة من المتحكم

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | المسار حيث سيتم إنشاء ملفات الفيديو والصوت |
| fileName | java.lang.String | اسم ملف HTML |
| baseUri | java.lang.String | عنوان الـ URI الأساسي الذي سيستخدم لإنشاء الروابط |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


يُستدعى لكتابة رأس مستند HTML. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


يُستدعى لكتابة تذييل مستند HTML. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


يُستدعى لكتابة رأس شريحة HTML. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


يُستدعى لكتابة تذييل شريحة HTML. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


يُستدعى قبل عرض الشكل. يُستدعى مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى المولد، ستنتهي عملية إنشاء صورة الشريحة الحالية، يتم إدراج الجزء المضاف من HTML وتبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


يُستدعى قبل عرض الشكل. يُستدعى مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى المولد، ستنتهي عملية إنشاء صورة الشريحة الحالية، يتم إدراج الجزء المضاف من HTML وتبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


تُستدعى هذه الدالة قبل تحويل الشكل إلى SVG للسماح للمستخدم بالتحكم في SVG الناتج.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


يحدد أين يجب تخزين الكائن. تُستدعى هذه الطريقة مرة واحدة لكل معرف كائن. لا يُضمن عدم وجود كائنين بنفس البيانات وsemanticName وcontentType ولكن بمعرف مختلف.

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


يرجع عنوان URL إلى كائن خارجي. تُستدعى هذه الطريقة دائمًا إذا كان \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) قد أرجع [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) وقد تُستدعى إذا كان \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) قد أرجع [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) لكن لا يمكن تضمينه. يمكن استدعاؤها عدة مرات لنفس معرف الكائن.

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