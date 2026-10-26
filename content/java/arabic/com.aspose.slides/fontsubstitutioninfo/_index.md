---
title: FontSubstitutionInfo
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل هذا الهيكل المعلومات حول استبدال الخط عند عرضه.
type: docs
url: /ar/com.aspose.slides/fontsubstitutioninfo/
---
**الوراثة:**
java.lang.Object
```
public class FontSubstitutionInfo
```

يمثل هذا الهيكل المعلومات حول استبدال الخط عند عرضه.

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
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | ينشئ مثالا من الفئة [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | يشير إلى اسم الخط المصدر في العرض. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | يشير إلى اسم الخط البديل للخط الأصلي. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


ينشئ مثالا من الفئة [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| originFontName | java.lang.String | اسم الخط المصدر في العرض String |
| substFontName | java.lang.String | اسم الخط البديل للخط الأصلي String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


يشير إلى اسم الخط المصدر في العرض. لقراءة فقط String

**القيمة المرجعة:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


يشير إلى اسم الخط البديل للخط الأصلي. لقراءة فقط String

**القيمة المرجعة:**
java.lang.String