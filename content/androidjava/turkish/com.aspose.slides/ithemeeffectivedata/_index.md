---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Etkili tema özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Etkili tema özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [ITheme](../../com.aspose.slides/itheme) arayüzüyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Renk şemasını döndürür. |
| [getFontScheme()](#getFontScheme--) | Yazı tipi şemasını döndürür. |
| [getFormatScheme()](#getFormatScheme--) | Şekil biçim şemasını döndürür. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

Renk şemasını döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Döndürür:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Renk şeması [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Yazı tipi şemasını döndürür. Salt okunur [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Döndürür:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Şekil biçim şemasını döndürür. Salt okunur [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Döndürür:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)