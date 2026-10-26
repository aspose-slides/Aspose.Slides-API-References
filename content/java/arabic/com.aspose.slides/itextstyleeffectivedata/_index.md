---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص نمط النص الفعّال.
type: docs
url: /ar/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص نمط النص الفعّال.

--------------------

يُستخدم هذا الواجهة مع واجهة [ITextStyle](../../com.aspose.slides/itextstyle) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | يرجع مستوى النمط الفعّال. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | يرجع خصائص الفقرة الافتراضية الفعّالة. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

يرجع مستوى النمط الفعّال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس صفر-مبني للمستوى. يجب أن يكون ضمن الفاصل 0..8. |

**الإرجاع:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - تنسيق الفعّال للمستوى [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

يرجع خصائص الفقرة الافتراضية الفعّالة. للقراءة فقط [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**الإرجاع:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)