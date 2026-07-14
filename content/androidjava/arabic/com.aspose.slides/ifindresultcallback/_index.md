---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: واجهة رد النداء المستخدمة للحصول على نتيجة البحث النصي.
type: docs
url: /ar/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

واجهة رد النداء المستخدمة للحصول على نتيجة البحث النصي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | طريقة رد النداء التي تتلقى البيانات حول النص الموجود. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


طريقة رد النداء التي تتلقى البيانات حول النص الموجود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | ال[ITextFrame](../../com.aspose.slides/itextframe) التي تم العثور على النص فيها. |
| sourceText | java.lang.String | النص المصدر الذي تم العثور على النص فيه. |
| foundText | java.lang.String | النص الموجود. |
| textPosition | int | موضع النص الموجود. |