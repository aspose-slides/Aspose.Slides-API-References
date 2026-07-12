---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto inmutable que contiene propiedades efectivas del esquema de fuentes.
type: docs
url: /es/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Objeto inmutable que contiene propiedades efectivas del esquema de fuentes.

--------------------

Esta interfaz se usa como parte de [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).

## Métodos

| Método | Descripción |
| --- | --- |
| [getMinor()](#getMinor--) | Devuelve la colección de fuentes para la parte "cuerpo" de la diapositiva. |
| [getMajor()](#getMajor--) | Devuelve la colección de fuentes para la parte "encabezado" de la diapositiva. |
| [getName()](#getName--) | Devuelve el nombre del esquema de fuentes. |

### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Devuelve la colección de fuentes para la parte "cuerpo" de la diapositiva. Solo lectura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Devuelve:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)

### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Devuelve la colección de fuentes para la parte "encabezado" de la diapositiva. Solo lectura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Devuelve:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)

### getName() {#getName--}
```
public abstract String getName()
```

Devuelve el nombre del esquema de fuentes. Solo lectura String.

**Devuelve:**
java.lang.String