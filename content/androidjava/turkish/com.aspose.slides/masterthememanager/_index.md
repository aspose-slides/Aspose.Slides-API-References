---
title: MasterThemeManager
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Sunum ana temasına erişim sağlar.
type: docs
url: /tr/com.aspose.slides/masterthememanager/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Sunum ana tema erişimi sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Geçersiz kılan tema nesnesini döndürür. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Geçersiz kılan tema nesnesini döndürür. |
| [createThemeEffective()](#createThemeEffective--) | Tema nesnesini döndürür. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme'in devralınan etkili temayı (Presentation.MasterTheme) geçersiz kılıp kılmadığını belirler. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | OverrideTheme'in devralınan etkili temayı (Presentation.MasterTheme) geçersiz kılıp kılmadığını belirler. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Bir slayta ek renk şeması uygular. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Geçersiz kılan tema nesnesini döndürür. Okuma/yazma [IMasterTheme](../../com.aspose.slides/imastertheme).

**Döndürür:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Geçersiz kılan tema nesnesini döndürür. Okuma/yazma [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Tema nesnesini döndürür.

**Döndürür:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


OverrideTheme'in devralınan etkili temayı (Presentation.MasterTheme) geçersiz kılıp kılmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


OverrideTheme'in devralınan etkili temayı (Presentation.MasterTheme) geçersiz kılıp kılmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Bir slayta ek renk şeması uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) nesnesi. |
