---
title: ITheme
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un tema.
type: docs
url: /es/com.aspose.slides/itheme/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Representa un tema.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Devuelve el esquema de color. |
| [getFontScheme()](#getFontScheme--) | Devuelve el esquema de fuentes. |
| [getFormatScheme()](#getFormatScheme--) | Devuelve el esquema de formato de forma. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del tema con la herencia aplicada. |
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

Devuelve el esquema de fuentes. Solo lectura [IFontScheme](../../com.aspose.slides/ifontscheme).

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

Obtiene los datos efectivos del tema con la herencia aplicada.

**Devuelve:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - un [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).