---
title: MasterTheme
second_title: Aspose.Slides para Android mediante la referencia de API de Java
description: Representa un tema maestro.
type: docs
url: /es/com.aspose.slides/mastertheme/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Representa un tema maestro.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Devuelve el esquema de colores. |
| [getFontScheme()](#getFontScheme--) | Devuelve el esquema de fuentes. |
| [getFormatScheme()](#getFormatScheme--) | Devuelve el esquema de formato de formas. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Devuelve la colección de esquemas de colores adicionales. |
| [getName()](#getName--) | Devuelve el nombre de un tema. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve el nombre de un tema. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Devuelve el esquema de colores. Solo lectura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Devuelve:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Devuelve el esquema de fuentes. Solo lectura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Devuelve:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Devuelve el esquema de formato de formas. Solo lectura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Devuelve:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Devuelve la colección de esquemas de colores adicionales. Estos esquemas no afectan el aspecto de la presentación, pueden seleccionarse como esquema de colores principal para una diapositiva. Solo lectura [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Devuelve:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Devuelve el nombre de un tema. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Devuelve el nombre de un tema. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long