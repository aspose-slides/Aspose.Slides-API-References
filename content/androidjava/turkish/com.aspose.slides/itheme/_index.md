---
title: ITheme
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir temayı temsil eder.
type: docs
url: /tr/com.aspose.slides/itheme/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Bir temayı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Renk şemasını döndürür. |
| [getFontScheme()](#getFontScheme--) | Yazı tipi şemasını döndürür. |
| [getFormatScheme()](#getFormatScheme--) | Şekil formatı şemasını döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili tema verilerini alır. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Renk şemasını döndürür. Salt okunur [IColorScheme](../../com.aspose.slides/icolorscheme).

**Döndürür:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Yazı tipi şemasını döndürür. Salt okunur [IFontScheme](../../com.aspose.slides/ifontscheme).

**Döndürür:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Şekil formatı şemasını döndürür. Salt okunur [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Döndürür:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Kalıtım uygulanmış etkili tema verilerini alır.

**Döndürür:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Bir [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).