---
title: BaseOverrideThemeManager
second_title: Referencia de API de Aspose.Slides para Java
description: Clase base para clases que proporcionan acceso a diferentes tipos de temas sobrescritos.
type: docs
url: /es/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Clase base para clases que proporcionan acceso a diferentes tipos de temas sobrescritos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Devuelve el objeto de tema de anulación. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Devuelve el objeto de tema de anulación. |
| [createThemeEffective()](#createThemeEffective--) | Devuelve el objeto de tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina si OverrideTheme sobrescribe el tema efectivo heredado o no. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Aplica un esquema de colores adicional a una diapositiva. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Devuelve el objeto de tema de anulación. Lectura/escritura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Devuelve:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Devuelve el objeto de tema de anulación. Lectura/escritura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

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

Determina si OverrideTheme sobrescribe el tema efectivo heredado o no. Para habilitar OverrideTheme para sobrescribir, use los métodos OverrideTheme.Init\*(). Para deshabilitar OverrideTheme de sobrescribir, use el método OverrideTheme.Clear(). Booleano de solo lectura.

**Devuelve:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Aplica un esquema de colores adicional a una diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | El objeto [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |