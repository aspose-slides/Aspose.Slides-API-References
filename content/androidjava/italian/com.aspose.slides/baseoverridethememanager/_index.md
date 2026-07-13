---
title: BaseOverrideThemeManager
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Classe base per le classi che forniscono l'accesso a diversi tipi di temi sovrascritti.
type: docs
url: /it/com.aspose.slides/baseoverridethememanager/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Tutte le interfacce implementate:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Classe base per le classi che forniscono l'accesso a diversi tipi di temi sovrascritti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Restituisce l'oggetto tema sovrascritto. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Restituisce l'oggetto tema sovrascritto. |
| [createThemeEffective()](#createThemeEffective--) | Restituisce l'oggetto tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina se OverrideTheme sovrascrive il tema efficace ereditato o meno. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applica uno schema di colori extra a una diapositiva. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Restituisce l'oggetto tema sovrascritto. Lettura/scrittura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Restituisce:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Restituisce l'oggetto tema sovrascritto. Lettura/scrittura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Restituisce l'oggetto tema.

**Restituisce:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Determina se OverrideTheme sovrascrive il tema efficace ereditato o meno. Per abilitare OverrideTheme per la sovrascrittura, utilizzare i metodi OverrideTheme.Init\*(). Per disabilitare OverrideTheme dalla sovrascrittura, utilizzare il metodo OverrideTheme.Clear(). Booleano di sola lettura.

**Restituisce:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Applica uno schema di colori extra a una diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | L'oggetto [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |