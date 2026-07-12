---
title: IThemeEffectiveData
second_title: Aspose.Slides para Android a través de la referencia de API Java
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
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Devuelve el esquema de colores. |
| [getFontScheme()](#getFontScheme--) | Devuelve el esquema de fuentes. |
| [getFormatScheme()](#getFormatScheme--) | Devuelve el esquema de formato de forma. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Devuelve el esquema de colores.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Devuelve:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - esquema de colores [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Devuelve el esquema de fuentes. Sólo lectura [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Devuelve:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Devuelve el esquema de formato de forma. Sólo lectura [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Devuelve:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)