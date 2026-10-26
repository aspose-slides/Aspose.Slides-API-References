---
title: LinkEmbedDecision
second_title: مرجع API الخاص بـ Aspose.Slides للغة Java
description: يحدد كيفية معالجة الكائن أثناء الحفظ.
type: docs
url: /ar/com.aspose.slides/linkembeddecision/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

يحدد كيفية معالجة الكائن أثناء الحفظ.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Link](#Link) | سيتم تخزين الكائن خارجيًا، مع الإشارة إليه عبر URL |
| [Embed](#Embed) | يجب تضمين الكائن في ملف مُنشأ إذا كان ذلك ممكنًا. |
| [Ignore](#Ignore) | سيتم تجاهل الكائن. |
### رابط {#Link}
```
public static final int Link
```


سيتم تخزين الكائن خارجيًا، مع الإشارة إليه عبر URL

### تضمين {#Embed}
```
public static final int Embed
```


يجب تضمين الكائن في ملف مُنشأ إذا كان ذلك ممكنًا. إذا كان التضمين غير ممكن، سيتم استدعاء GetUrl، وبحسب النتيجة، سيتم الإشارة إلى الكائن عبر URL أو تجاهله.

### تجاهل {#Ignore}
```
public static final int Ignore
```


سيتم تجاهل الكائن.