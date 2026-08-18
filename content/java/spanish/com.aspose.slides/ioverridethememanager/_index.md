---
title: IOverrideThemeManager
second_title: Referencia de API de Aspose.Slides para Java
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
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina si OverrideTheme anula el tema efectivo heredado o no. |
| [getOverrideTheme()](#getOverrideTheme--) | Devuelve el objeto de tema de anulación. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Devuelve el objeto de tema de anulación. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Determina si OverrideTheme anula el tema efectivo heredado o no. Para habilitar OverrideTheme para la anulación, use los métodos OverrideTheme.Init\*(). Para deshabilitar OverrideTheme de la anulación, use el método OverrideTheme.Clear(). Booleano de solo lectura.

**Devuelve:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Devuelve el objeto de tema de anulación. Lectura/escritura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Devuelve:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Devuelve el objeto de tema de anulación. Lectura/escritura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |