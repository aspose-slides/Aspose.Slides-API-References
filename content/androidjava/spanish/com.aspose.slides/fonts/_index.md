---
title: Fonts
second_title: Referencia API Java de Aspose.Slides para Android
description: Colección de fuentes.
type: docs
url: /es/com.aspose.slides/fonts/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Colección de fuentes.
## Methods

| Method | Description |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Devuelve un diccionario de todas las definiciones de fuentes de script en la presentación. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Obtiene el nombre de la fuente asociado a una etiqueta de script específica del tema de la presentación. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Asigna un nombre de fuente a una etiqueta de script específica, lo que define cómo se renderizará el texto de ese script en la presentación. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Elimina la configuración de fuente asociada a una etiqueta de script específica de la colección de fuentes del tema. |
| [getLatinFont()](#getLatinFont--) | Devuelve o establece la fuente latina. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Devuelve o establece la fuente latina. |
| [getEastAsianFont()](#getEastAsianFont--) | Devuelve o establece la fuente de Asia oriental. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Devuelve o establece la fuente de Asia oriental. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Devuelve o establece la fuente de script complejo. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Devuelve o establece la fuente de script complejo. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Un diccionario que asigna códigos de script a nombres de fuentes.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
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
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | El código de script BCP-47 (p. ej., "Latn", "Cyrl", "Jpan") usado para identificar un sistema de escritura. |

**Devuelve:**
java.lang.String - El nombre de la fuente usado para el script especificado, o  null  si el script no está definido.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Asigna un nombre de fuente a una etiqueta de script específica, lo que define cómo se renderizará el texto de ese script en la presentación.

--------------------

> ```
> Este ejemplo muestra cómo establecer la fuente para el script árabe a "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | El código de script BCP-47 (p. ej., "Arab", "Hebr", "Hans") que identifica el sistema de escritura. |
| fontName | java.lang.String | El nombre de la fuente a asignar al script especificado. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Elimina la configuración de fuente asociada a una etiqueta de script específica de la colección de fuentes del tema.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | El código de script BCP-47 cuya configuración de fuente debe eliminarse. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Devuelve o establece la fuente latina. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Devuelve o establece la fuente latina. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Devuelve o establece la fuente de Asia oriental. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Devuelve o establece la fuente de Asia oriental. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Devuelve o establece la fuente de script complejo. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Devuelve o establece la fuente de script complejo. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |