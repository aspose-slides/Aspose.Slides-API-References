---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /ar/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

واجهة رد الاتصال المستخدمة للحصول على نتيجة البحث النصي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | طريقة رد الاتصال التي تستقبل بيانات حول النص المعثور عليه. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


طريقة رد الاتصال التي تستقبل بيانات حول النص المعثور عليه.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | الـ [ITextFrame](../../com.aspose.slides/itextframe) التي تم العثور على النص فيها. |
| sourceText | java.lang.String | نص المصدر الذي تم العثور على النص فيه. |
| foundText | java.lang.String | النص المعثور عليه. |
| textPosition | int | موضع النص المعثور عليه. |