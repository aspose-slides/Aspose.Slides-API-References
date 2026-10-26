---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Java API Referansı
description: Farklı türde geçersiz kılınmış temalara erişim sağlayan sınıflar için temel sınıf.
type: docs
url: /tr/com.aspose.slides/baseoverridethememanager/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Farklı türde geçersiz kılınmış temalara erişim sağlayan sınıflar için temel sınıf.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Geçersiz kılma teması nesnesini döndürür. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Geçersiz kılma teması nesnesini döndürür. |
| [createThemeEffective()](#createThemeEffective--) | Tema nesnesini döndürür. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme'in kalıtılan etkili temayı geçersiz kılıp kılmadığını belirler. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Bir slayta ekstra renk şeması uygular. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Geçersiz kılma teması nesnesini döndürür. Okunur/yazılır [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Döndürür:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Geçersiz kılma teması nesnesini döndürür. Okunur/yazılır [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

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


OverrideTheme'in kalıtılan etkili temayı geçersiz kılıp kılmadığını belirler. OverrideTheme'i geçersiz kılma için etkinleştirmek OverrideTheme.Init\*() yöntemlerini kullanın. OverrideTheme'in geçersiz kılmasını devre dışı bırakmak için OverrideTheme.Clear() yöntemini kullanın. Yalnızca okunur boolean.

**Döndürür:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Bir slayta ekstra renk şeması uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) nesnesi. |