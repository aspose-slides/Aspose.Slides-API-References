---
title: FontSubstitutionInfo
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل هذا الهيكل المعلومات حول استبدال الخط عندما يتم عرضه.
type: docs
url: /ar/com.aspose.slides/fontsubstitutioninfo/
---
**الوراثة:**
java.lang.Object
```
public class FontSubstitutionInfo
```

يمثل هذا الهيكل المعلومات حول استبدال الخط عندما يتم عرضه.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | ينشئ كائنًا من فئة [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | يشير إلى اسم الخط المصدر في العرض التقديمي. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | يشير إلى اسم الخط البديل للخط الأصلي. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

ينشئ كائنًا من فئة [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| originFontName | java.lang.String | اسم الخط المصدر في العرض التقديمي String |
| substFontName | java.lang.String | اسم الخط البديل للخط الأصلي String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

يشير إلى اسم الخط المصدر في العرض التقديمي. قراءة فقط String

**القيمة المرجعة:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

يشير إلى اسم الخط البديل للخط الأصلي. قراءة فقط String

**القيمة المرجعة:**
java.lang.String