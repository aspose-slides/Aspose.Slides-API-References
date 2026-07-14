---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: خصائص تنسيق نمط النص.
type: docs
url: /ar/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

خصائص تنسيق نمط النص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | إذا كان مستوى النمط موجودًا، تُرجعه؛ وإلا تُرجع null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | خصائص الفقرة الافتراضية. |
| [getEffective()](#getEffective--) | يجلب بيانات تنسيق نمط النص الفعّالة مع تطبيق الوراثة. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```


إذا كان مستوى النمط موجودًا، تُرجعه؛ وإلا تُرجع null.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس المستوى يبدأ من صفر. يجب أن يكون ضمن الفاصل 0..8. |

**القيمة المرجعة:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - تنسيق المستوى [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```


خصائص الفقرة الافتراضية. للقراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**القيمة المرجعة:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```


يجلب بيانات تنسيق نمط النص الفعّالة مع تطبيق الوراثة.

**القيمة المرجعة:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - كائن [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).