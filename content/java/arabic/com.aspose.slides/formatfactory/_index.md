---
title: FormatFactory
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يسمح بإنشاء الصيغ عبر واجهة COM.
type: docs
url: /ar/com.aspose.slides/formatfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

يسمح بإنشاء الصيغ عبر واجهة COM.

## البنائين

| المنشئ | الوصف |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInstance()](#getInstance--) | مثيل ثابت لمصنع الصيغ. |
| [createPortionFormat()](#createPortionFormat--) | ينشئ [IPortionFormat](../../com.aspose.slides/iportionformat) جديداً. |
| [createParagraphFormat()](#createParagraphFormat--) | ينشئ [IParagraphFormat](../../com.aspose.slides/iparagraphformat) جديداً. |
| [createTextFrameFormat()](#createTextFrameFormat--) | ينشئ [ITextFrameFormat](../../com.aspose.slides/itextframeformat) جديداً. |

### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

مثيل ثابت لمصنع الصيغ. للقراءة فقط [FormatFactory](../../com.aspose.slides/formatfactory).

**الإرجاع:**
[FormatFactory](../../com.aspose.slides/formatfactory)

### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

ينشئ [IPortionFormat](../../com.aspose.slides/iportionformat) جديداً.

**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - تنسيق جزء جديد.

### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

ينشئ [IParagraphFormat](../../com.aspose.slides/iparagraphformat) جديداً.

**الإرجاع:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - تنسيق الفقرة الجديد.

### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

ينشئ [ITextFrameFormat](../../com.aspose.slides/itextframeformat) جديداً.

**الإرجاع:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - تنسيق إطار النص الجديد.