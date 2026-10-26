---
title: BaseOverrideThemeManager
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Základní třída pro třídy, které poskytují přístup k různým typům přepsaných motivů.
type: docs
url: /cs/com.aspose.slides/baseoverridethememanager/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Všechny implementované rozhraní:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Základní třída pro třídy, které poskytují přístup k různým typům přepsaných motivů.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Vrací objekt přepisující motiv. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Vrací objekt přepisující motiv. |
| [createThemeEffective()](#createThemeEffective--) | Vrací objekt motivu. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv, nebo ne. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Použije další barevné schéma na snímek. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Vrací objekt přepisující motiv. Čtení/zápis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Vrací:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Vrací objekt přepisující motiv. Čtení/zápis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Vrací objekt motivu.

**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv, nebo ne. Pro povolení přepisování OverrideTheme použijte metody OverrideTheme.Init\*(). Pro zakázání přepisování OverrideTheme použijte metodu OverrideTheme.Clear(). Pouze pro čtení boolean.

**Vrací:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Použije další barevné schéma na snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Objekt [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |