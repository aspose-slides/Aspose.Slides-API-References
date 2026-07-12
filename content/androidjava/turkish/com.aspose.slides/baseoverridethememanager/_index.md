---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Android via Java API Referansı
description: Farklı tipte geçersiz kılınmış temalara erişim sağlayan sınıflar için temel sınıf.
type: docs
url: /tr/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Farklı tipte geçersiz kılınmış temalara erişim sağlayan sınıflar için temel sınıf.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Geçersiz kılınan tema nesnesini döndürür. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Geçersiz kılınan tema nesnesini döndürür. |
| [createThemeEffective()](#createThemeEffective--) | Tema nesnesini döndürür. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme'in kalıtılan etkili temayı geçersiz kılıp kılmadığını belirler. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Bir slayta ekstra renk şemasını uygular. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Geçersiz kılınan tema nesnesini döndürür. Okuma/Yazma [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Döndürür:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Geçersiz kılınan tema nesnesini döndürür. Okuma/Yazma [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |
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

OverrideTheme'in kalıtılan etkili temayı geçersiz kılıp kılmadığını belirler. OverrideTheme'i geçersiz kılma için etkinleştirmek amacıyla OverrideTheme.Init*() yöntemlerini kullanın. OverrideTheme'i geçersiz kılmadan devre dışı bırakmak için OverrideTheme.Clear() yöntemini kullanın. Yalnızca-okunur boolean.

**Döndürür:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Bir slayta ekstra renk şemasını uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) nesnesi. |