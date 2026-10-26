---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls a html file generation.
type: docs
url: /ar/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

يتحكم في إنشاء ملف HTML.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | يُستدعى لكتابة رأس مستند html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | يُستدعى لكتابة تذييل مستند html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | يُستدعى لكتابة رأس شريحة html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | يُستدعى لكتابة تذييل شريحة html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | يُستدعى قبل تصيير الشكل. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | يُستدعى قبل تصيير الشكل. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

يُستدعى لكتابة رأس مستند html. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض الذي يتم تقديمه حاليًا. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

يُستدعى لكتابة تذييل مستند html. يُستدعى مرة واحدة لكل تحويل عرض تقديمي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض الذي يتم تقديمه حاليًا. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

يُستدعى لكتابة رأس شريحة html. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي يتم تقديمها حاليًا. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

يُستدعى لكتابة تذييل شريحة html. يُستدعى مرة واحدة لكل شريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي يتم تقديمها حاليًا. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

يُستدعى قبل تصيير الشكل. يُستدعى مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى generator، سيتم الانتهاء من إنشاء صورة الشريحة الحالية، وسيُدرج الجزء المضاف من html، وسيُبدأ إنشاء صورة جديدة فوق السابقة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي على وشك التصيير. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

يُستدعى قبل تصيير الشكل. يُستدعى مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى generator، سيتم الانتهاء من إنشاء صورة الشريحة الحالية، وسيُدرج الجزء المضاف من html، وسيُبدأ إنشاء صورة جديدة فوق السابقة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | كائن الإخراج. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي تم تصييره آخرًا. |