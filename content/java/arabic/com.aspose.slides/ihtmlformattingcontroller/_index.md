---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: يتحكم في إنشاء ملف html.
type: docs
url: /ar/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

يتحكم في إنشاء ملف html.
## الطرق

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | يُستدعى لكتابة رأس مستند html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | يُستدعى لكتابة تذييل مستند html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | يُستدعى لكتابة رأس شريحة html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | يُستدعى لكتابة تذييل شريحة html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | يُستدعى قبل عرض الشكل. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | يُستدعى قبل عرض الشكل. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

يُستدعى لكتابة رأس مستند html. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي الذي يجري عرضه حالياً. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

يُستدعى لكتابة تذييل مستند html. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي الذي يجري عرضه حالياً. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

يُستدعى لكتابة رأس شريحة html. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي يجري عرضها حالياً. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

يُستدعى لكتابة تذييل شريحة html. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي يجري عرضها حالياً. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

يُستدعى قبل عرض الشكل. يُستدعى مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى المولد، سيتم إكمال توليد صورة الشريحة الحالية، وإدراج الجزء المضاف من html، وستبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي على وشك العرض. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

يُستدعى قبل عرض الشكل. يُستدعى مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى المولد، سيتم إكمال توليد صورة الشريحة الحالية، وإدراج الجزء المضاف من html، وستبدأ صورة جديدة فوق السابقة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي تم عرضه آخراً. |