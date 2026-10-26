---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a font definition.
type: docs
url: /ar/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

يمثل تعريف خط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getFontName()](#getFontName--) | يعيد اسم الخط. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | يعيد اسم الخط، مع استبدال إشارة السمة بخط فعلي مُستخدم. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

يعيد اسم الخط. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

يعيد اسم الخط، مع استبدال إشارة السمة بخط فعلي مُستخدم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | السمة التي يجب أخذ اسم الخط الموجَّه منها. الأمر متروك للمتصل لتوفير قيمة صحيحة. |

**الإرجاع:**
java.lang.String - اسم الخط.