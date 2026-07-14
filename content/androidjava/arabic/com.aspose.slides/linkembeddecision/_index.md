---
title: LinkEmbedDecision
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: تحدد كيف سيتم معالجة الكائن أثناء الحفظ.
type: docs
url: /ar/com.aspose.slides/linkembeddecision/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

تحدد كيف سيتم معالجة الكائن أثناء الحفظ.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Link](#Link) | سيتم تخزين الكائن خارجيًا، مُشارًا إليه عبر URL |
| [Embed](#Embed) | يجب تضمين الكائن في ملف مُولد إذا كان ذلك ممكنًا. |
| [Ignore](#Ignore) | سيتم تجاهل الكائن. |
### الرابط {#Link}
```
public static final int Link
```


سيتم تخزين الكائن خارجيًا، مُشارًا إليه عبر URL

### التضمين {#Embed}
```
public static final int Embed
```


يجب تضمين الكائن في ملف مُولد إذا كان ذلك ممكنًا. إذا كان التضمين غير ممكن، سيتم استدعاء GetUrl، واعتمادًا على النتيجة، سيتم الإشارة إلى الكائن عبر URL أو تجاهله.

### التجاهل {#Ignore}
```
public static final int Ignore
```


سيتم تجاهل الكائن.