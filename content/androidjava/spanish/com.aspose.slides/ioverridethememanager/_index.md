---
title: IOverrideThemeManager
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Proporciona acceso a diferentes tipos de temas anulados.
type: docs
url: /es/com.aspose.slides/ioverridethememanager/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Proporciona acceso a diferentes tipos de temas anulados.
## Métodos

| Método | Descripción |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina si OverrideTheme sobrescribe el tema efectivo heredado o no. |
| [getOverrideTheme()](#getOverrideTheme--) | Devuelve el objeto de tema de sobrescritura. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Devuelve el objeto de tema de sobrescritura. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Determina si OverrideTheme sobrescribe el tema efectivo heredado o no. Para habilitar OverrideTheme para sobrescribir use los métodos OverrideTheme.Init\*(). Para deshabilitar OverrideTheme de sobrescribir use el método OverrideTheme.Clear(). Solo lectura boolean.

**Devuelve:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Devuelve el objeto de tema de sobrescritura. Lectura/escritura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Devuelve:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Devuelve el objeto de tema de sobrescritura. Lectura/escritura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |