---
title: FormatFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يسمح بإنشاء الصيغ عبر واجهة COM.
type: docs
url: /ar/com.aspose.slides/formatfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المطبقة:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

يسمح بإنشاء الصيغ عبر واجهة COM.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInstance()](#getInstance--) | مثيل ثابت لمصنع الصيغ. |
| [createPortionFormat()](#createPortionFormat--) | ينشئ جديد [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | ينشئ جديد [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | ينشئ جديد [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


مثيل ثابت لمصنع الصيغ. للقراءة فقط [FormatFactory](../../com.aspose.slides/formatfactory).

**القيمة المرجعة:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


ينشئ جديد [IPortionFormat](../../com.aspose.slides/iportionformat).

**القيمة المرجعة:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - صيغة جزء جديدة.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


ينشئ جديد [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**القيمة المرجعة:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - صيغة فقرة جديدة.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


ينشئ جديد [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**القيمة المرجعة:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - صيغة إطار نص جديد.