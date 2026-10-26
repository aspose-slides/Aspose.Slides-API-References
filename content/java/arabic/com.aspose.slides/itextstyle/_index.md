---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: خصائص تنسيق نمط النص.
type: docs
url: /ar/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

خصائص تنسيق نمط النص.
## Methods

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | إذا كان مستوى النمط موجودًا فسيتم إرجاعه، وإلا سيتم إرجاع null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | خصائص الفقرة الافتراضية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق نمط النص الفعلي مع تطبيق الوراثة. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

إذا كان مستوى النمط موجودًا فسيتم إرجاعه، وإلا سيتم إرجاع null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | مؤشر يبدأ من الصفر للمستوى. يجب أن يكون في المجال 0..8. |

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - تنسيق المستوى [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

خصائص الفقرة الافتراضية. قراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

يحصل على بيانات تنسيق نمط النص الفعلي مع تطبيق الوراثة.

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - كائن [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).