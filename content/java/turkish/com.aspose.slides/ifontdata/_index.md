---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
type: docs
url: /tr/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Bir yazı tipi tanımını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontName()](#getFontName--) | Yazı tipi adını döndürür. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Yazı tipi adını döndürür, tema referansını kullanılan gerçek bir yazı tipiyle değiştirir. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Yazı tipi adını döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Yazı tipi adını döndürür, tema referansını kullanılan gerçek bir yazı tipiyle değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Temalı yazı tipi adının alınacağı tema. Doğru bir değer sağlamak çağıranın sorumluluğundadır. |

**Döndürür:**
java.lang.String - Yazı tipi adı.