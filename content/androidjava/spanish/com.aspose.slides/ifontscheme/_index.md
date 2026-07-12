---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: Almacena fuentes definidas por el tema.
type: docs
url: /es/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Almacena fuentes definidas por el tema.
## Métodos

| Método | Descripción |
| --- | --- |
| [getMinor()](#getMinor--) | Devuelve la colección de fuentes para la parte "body" de la diapositiva. |
| [getMajor()](#getMajor--) | Devuelve la colección de fuentes para la parte "heading" de la diapositiva. |
| [getName()](#getName--) | Devuelve el nombre del esquema de fuentes. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve el nombre del esquema de fuentes. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Devuelve la colección de fuentes para la parte "body" de la diapositiva. Solo lectura [IFonts](../../com.aspose.slides/ifonts).

**Devuelve:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Devuelve la colección de fuentes para la parte "heading" de la diapositiva. Solo lectura [IFonts](../../com.aspose.slides/ifonts).

**Devuelve:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Devuelve el nombre del esquema de fuentes. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Devuelve el nombre del esquema de fuentes. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |