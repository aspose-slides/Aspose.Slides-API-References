---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص نمط النص الفعلي.
type: docs
url: /ar/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص نمط النص الفعلي.

--------------------

يتم استخدام هذه الواجهة مع الواجهة [ITextStyle](../../com.aspose.slides/itextstyle) لإرجاع قيم التنسيق الفعلي مع تطبيق الإرث.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | يعيد مستوى النمط الفعلي. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | يعيد خصائص الفقرة الافتراضية الفعلية. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

يعيد مستوى النمط الفعلي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للمستوى. يجب أن يكون في النطاق 0..8. |

**القيمة المرجعة:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - التنسيق الفعال للمستوى [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

يعيد خصائص الفقرة الافتراضية الفعلية. للقراءة فقط [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**القيمة المرجعة:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)