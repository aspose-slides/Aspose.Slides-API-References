---
title: IOverridableText
second_title: مرجع API الخاص بـ Aspose.Slides للغة Java
description: يمثّل النص القابل للكتابة فوقه في المخطط.
type: docs
url: /ar/com.aspose.slides/ioverridabletext/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

يمثّل النص القابل للكتابة فوقه في المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | يمكن أن يحتوي على نص منسّق غني. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | تُهيئ TextFrameForOverriding بالنص في المعامل "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

يمكن أن يحتوي على نص منسّق غني. إذا كانت هذه الخاصية غير فارغة فإن قيمة النص المنسّق هذه تحلّ محل النص المُنشأ آلياً. النص المُنشأ آلياً هو خاصية ضمنية لعلامة البيانات، ولعلامة وحدة العرض لمحور القيم، وعنوان المحور، وعنوان المخطط، وعلامة خط الاتجاه. النص المُنشأ آلياً يُنسق باستخدام الخاصية IFormattedTextContainer.TextFormat. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

تُهيئ TextFrameForOverriding بالنص في المعامل "text". إذا كان TextFrameForOverriding مُهيئاً مسبقاً فسيتم فقط تغيير نصه.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص لإطار TextFrameForOverriding جديد. |

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe) - إطار نص [ITextFrame](../../com.aspose.slides/itextframe)