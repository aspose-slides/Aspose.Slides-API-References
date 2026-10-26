---
title: IFontData
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir yazı tipi tanımını temsil eder.
type: docs
url: /tr/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Bir yazı tipi tanımını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontName()](#getFontName--) | Returns the font name. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returns the font name, replacing theme referrence with an actual font used. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Yazı tipi adını döndürür. Salt okunur String.

### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Yazı tipi adını döndürür, tema referansını gerçek kullanılan yazı tipiyle değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema, temalı yazı tipi adının alınması gereken yer. Doğru bir değer sağlamak çağıranın sorumluluğundadır. |

**Döndürür:**
java.lang.String - Yazı tipi adı.