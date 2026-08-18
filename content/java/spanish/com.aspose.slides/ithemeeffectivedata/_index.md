---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objeto inmutable que contiene propiedades de tema efectivas.
type: docs
url: /es/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Objeto inmutable que contiene propiedades de tema efectivas.

--------------------

Esta interfaz se usa junto con la interfaz [ITheme](../../com.aspose.slides/itheme) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Devuelve el esquema de colores. |
| [getFontScheme()](#getFontScheme--) | Devuelve el esquema de fuentes. |
| [getFormatScheme()](#getFormatScheme--) | Devuelve el esquema de formato de forma. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

Devuelve el esquema de colores.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Devuelve:**  
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - esquema de colores [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Devuelve el esquema de fuentes. Solo lectura [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Devuelve:**  
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Devuelve el esquema de formato de forma. Solo lectura [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Devuelve:**  
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)