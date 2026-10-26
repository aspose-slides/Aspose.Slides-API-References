---
title: MasterThemeManager
second_title: Aspose.Slides para Android mediante la referencia de la API de Java
description: Proporciona acceso al tema maestro de la presentación.
type: docs
url: /es/com.aspose.slides/masterthememanager/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Proporciona acceso al tema maestro de la presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Devuelve el objeto de tema de sustitución. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Devuelve el objeto de tema de sustitución. |
| [createThemeEffective()](#createThemeEffective--) | Devuelve el objeto de tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina si OverrideTheme sustituye el tema efectivo heredado (Presentation.MasterTheme) o no. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Determina si OverrideTheme sustituye el tema efectivo heredado (Presentation.MasterTheme) o no. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Aplica un esquema de color extra a una diapositiva. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Devuelve el objeto de tema de sustitución. Lectura/escritura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Devuelve:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Devuelve el objeto de tema de sustitución. Lectura/escritura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Devuelve el objeto de tema.

**Devuelve:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Determina si OverrideTheme sustituye el tema efectivo heredado (Presentation.MasterTheme) o no. Lectura/escritura boolean.

**Devuelve:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


Determina si OverrideTheme sustituye el tema efectivo heredado (Presentation.MasterTheme) o no. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Aplica un esquema de color extra a una diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objeto. |