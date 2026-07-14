---
title: IOverridableText
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل نصًا قابلاً للاستبدال لمخطط.
type: docs
url: /ar/com.aspose.slides/ioverridabletext/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

يمثل نصًا قابلًا للاستبدال لمخطط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | يمكن أن يحتوي على نص منسق غني. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | تعيين TextFrameForOverriding بالنص الموجود في المعامل "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية فارغة (null) فإن قيمة النص المنسق تتجاوز النص الذي تم إنشاؤه تلقائيًا. النص الذي تم إنشاؤه تلقائيًا هو خاصية ضمنية لتسمية البيانات، تسمية وحدة العرض لمحور القيمة، عنوان المحور، عنوان المخطط، تسمية خط الاتجاه. يتم تنسيق النص الذي تم إنشاؤه تلقائيًا باستخدام خاصية IFormattedTextContainer.TextFormat. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

تعيين TextFrameForOverriding بالنص الموجود في المعامل "text". إذا كان TextFrameForOverriding مُعَيَّنًا مسبقًا فإن النص يتغير ببساطة.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص لإطار TextFrameForOverriding الجديد. |

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe) - إطار النص [ITextFrame](../../com.aspose.slides/itextframe)