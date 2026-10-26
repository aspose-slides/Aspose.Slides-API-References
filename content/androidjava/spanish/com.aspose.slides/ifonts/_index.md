---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Representa la colección de fuentes.
type: docs
url: /es/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Representa la colección de fuentes.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Devuelve o establece la fuente Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Devuelve o establece la fuente Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Devuelve o establece la fuente East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Devuelve o establece la fuente East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Devuelve o establece la fuente complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Devuelve o establece la fuente complex script. |
| [getScriptFontMap()](#getScriptFontMap--) | Devuelve un diccionario de todas las definiciones de fuentes de script en la presentación. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Obtiene el nombre de la fuente asociado a una etiqueta de script específica del tema de la presentación. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Asigna un nombre de fuente a una etiqueta de script específica, que define cómo se renderizará el texto de ese script en la presentación. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Elimina la configuración de fuente asociada a una etiqueta de script específica de la colección de fuentes del tema. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Devuelve o establece la fuente Latin. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Devuelve o establece la fuente Latin. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Devuelve o establece la fuente East Asian. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Devuelve o establece la fuente East Asian. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Devuelve o establece la fuente complex script. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Devuelve o establece la fuente complex script. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Devuelve un diccionario de todas las definiciones de fuentes de script en la presentación.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Devuelve:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Un diccionario que asigna códigos de script a nombres de fuentes.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Obtiene el nombre de la fuente asociado a una etiqueta de script específica del tema de la presentación.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| script | java.lang.String | El código de script BCP-47 (p.ej., "Latn", "Cyrl", "Jpan") usado para identificar un sistema de escritura. |

**Devuelve:**
java.lang.String - El nombre de la fuente usado para el script especificado, o  null  si el script no está definido.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Asigna un nombre de fuente a una etiqueta de script específica, que define cómo se renderizará el texto de ese script en la presentación.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| script | java.lang.String | El código de script BCP-47 (p.ej., "Arab", "Hebr", "Hans") que identifica el sistema de escritura. |
| fontName | java.lang.String | El nombre de la fuente que se asignará al script especificado. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Elimina la configuración de fuente asociada a una etiqueta de script específica de la colección de fuentes del tema.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| script | java.lang.String | El código de script BCP-47 cuya configuración de fuente debe eliminarse. |