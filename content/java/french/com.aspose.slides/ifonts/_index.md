---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /fr/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Représente la collection de polices.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font. |
| [getScriptFontMap()](#getScriptFontMap--) | Returns a dictionary of all script font definitions in the presentation. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Gets the font name associated with a specific script tag from the presentation theme. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Removes the font setting associated with a specific script tag from the theme's font collection. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Renvoie ou définit la police latine. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Renvoie ou définit la police latine. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Renvoie ou définit la police est-asiatique. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Renvoie ou définit la police est-asiatique. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Renvoie ou définit la police de script complexe. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Renvoie ou définit la police de script complexe. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Renvoie un dictionnaire de toutes les définitions de police de script dans la présentation.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Renvoie :**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Un dictionnaire associant les codes de script aux noms de police.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Obtient le nom de la police associé à une balise de script spécifique dans le thème de la présentation.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| script | java.lang.String | Le code de script BCP-47 (par ex., "Latn", "Cyrl", "Jpan") utilisé pour identifier un système d’écriture. |

**Renvoie :**
java.lang.String - Le nom de la police utilisée pour le script spécifié, ou  null  si le script n’est pas défini.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Attribue un nom de police à une balise de script spécifique, ce qui définit la façon dont le texte de ce script sera rendu dans la présentation.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| script | java.lang.String | Le code de script BCP-47 (par ex., "Arab", "Hebr", "Hans") identifiant le système d’écriture. |
| fontName | java.lang.String | Le nom de la police à attribuer au script spécifié. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Supprime le paramètre de police associé à une balise de script spécifique de la collection de polices du thème.

--------------------

> ```
> Cet exemple montre comment supprimer le mappage de police pour le script hébreu :
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| script | java.lang.String | Le code de script BCP-47 dont le paramètre de police doit être supprimé. |