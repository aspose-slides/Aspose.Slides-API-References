---
title: ITheme
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un tema.
type: docs
url: /es/com.aspose.slides/itheme/
---
**Todas las Interfaces Implementadas:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Representa un tema.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Devuelve el esquema de color. |
| [getFontScheme()](#getFontScheme--) | Devuelve el esquema de fuente. |
| [getFormatScheme()](#getFormatScheme--) | Devuelve el esquema de formato de forma. |
| [getEffective()](#getEffective--) | Obtiene los datos de tema efectivos con la herencia aplicada. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Devuelve el esquema de color. Solo lectura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Devuelve:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Devuelve el esquema de fuente. Solo lectura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Devuelve:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Devuelve el esquema de formato de forma. Solo lectura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Devuelve:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Obtiene los datos de tema efectivos con la herencia aplicada.

**Devuelve:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Un [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).