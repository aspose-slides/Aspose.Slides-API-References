---
title: IFontData
second_title: Aspose.Slides لمرجع API الخاص بـ Java
description: تمثل تعريف الخط.
type: docs
url: /ar/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

تمثل تعريف الخط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontName()](#getFontName--) | يرجع اسم الخط. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | يرجع اسم الخط، مستبدلاً إشارة السمة بخط فعلي مستخدم. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

يرجع اسم الخط. String للقراءة فقط.

**الإرجاع:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

يرجع اسم الخط، مستبدلاً إشارة السمة بخط فعلي مستخدم.

**المعلمات:**
| معاملة | النوع | الوصف |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | السمة التي يجب أخذ اسم الخط المظهر منها. على المتصل توفير قيمة صحيحة. |

**الإرجاع:**
java.lang.String - اسم الخط.