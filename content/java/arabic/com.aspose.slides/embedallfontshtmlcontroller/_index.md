---
title: EmbedAllFontsHtmlController
second_title: مرجع API لـ Aspose.Slides للغة Java
description: فئة المتحكم بالتنسيق التي تُستخدم لتضمين جميع خطوط العروض التقديمية بصيغة WOFF.
type: docs
url: /ar/com.aspose.slides/embedallfontshtmlcontroller/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

فئة المتحكم بالتنسيق المستخدمة لتضمين جميع خطوط العرض التقديمي بتنسيق WOFF.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | ينشئ مثيلاً جديدًا |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | ينشئ مثيلاً جديدًا |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | يُستدعى لكتابة رأس مستند html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | يُستدعى لكتابة تذييل مستند html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | يُستدعى لكتابة رأس شريحة html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | يُستدعى لكتابة تذييل شريحة html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | يُستدعى قبل عرض الشكل. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | يُستدعى قبل عرض الشكل. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | اكتب جميع الخطوط الموجودة في [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | يكتب البيانات بصيغة base64 داخل مستند HTML نفسه |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


ينشئ مثيلاً جديدًا

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


ينشئ مثيلاً جديدًا

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | الخطوط التي يجب استثناها من التضمين |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


يُستدعى لكتابة رأس مستند html. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي الذي يتم عرضه حاليًا. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


يُستدعى لكتابة تذييل مستند html. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي الذي يتم عرضه حاليًا. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


يُستدعى لكتابة رأس شريحة html. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي يتم عرضها حاليًا. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


يُستدعى لكتابة تذييل شريحة html. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي يتم عرضها حاليًا. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


يُستدعى قبل عرض الشكل. يُستدعى مرة واحدة لكل شكل. إذا كتب هذا الدالة أي شيء إلى المُولد، سيتم إكمال توليد صورة الشريحة الحالية، يُدرج جزء html المضاف وتُبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي على وشك العرض. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


يُستدعى قبل عرض الشكل. يُستدعى مرة واحدة لكل شكل. إذا كتب هذا الدالة أي شيء إلى المُولد، سيتم إكمال توليد صورة الشريحة الحالية، يُدرج جزء html المضاف وتُبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي تم عرضه أخيرًا. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


اكتب جميع الخطوط الموجودة في [Presentation](../../com.aspose.slides/presentation).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي الذي يتم عرضه حاليًا. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


يكتب البيانات بصيغة base64 داخل مستند HTML نفسه

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | مولد HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | الخط الذي سيتم تسلسله |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | الخط المستبدل (إذا حدث استبدال الخط)، وإلا يكون null |
| fontStyle | java.lang.String | نمط الخط |
| fontWeight | java.lang.String | وزن الخط |
| fontData | byte[] | بيانات الخط |