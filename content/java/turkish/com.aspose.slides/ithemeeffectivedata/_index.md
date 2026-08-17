---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkili tema özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Etkili tema özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [ITheme](../../com.aspose.slides/itheme) arayüzü ile birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Renk şemasını döndürür. |
| [getFontScheme()](#getFontScheme--) | Yazı tipi şemasını döndürür. |
| [getFormatScheme()](#getFormatScheme--) | Şekil biçim şemasını döndürür. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

Renk şemasını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Döndürür:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
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