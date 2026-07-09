---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Représente la collection de polices.
type: docs
url: /fr/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Représente la collection de polices.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Retourne ou définit la police latine. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Retourne ou définit la police latine. |
| [getEastAsianFont()](#getEastAsianFont--) | Retourne ou définit la police d'Asie orientale. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Retourne ou définit la police d'Asie orientale. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retourne ou définit la police de script complexe. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Retourne ou définit la police de script complexe. |
| [getScriptFontMap()](#getScriptFontMap--) | Retourne un dictionnaire de toutes les définitions de polices de script dans la présentation. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Obtient le nom de police associé à une balise de script spécifique du thème de la présentation. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Assigne un nom de police à une balise de script spécifique, définissant la façon dont le texte de ce script sera rendu dans la présentation. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Supprime le paramètre de police associé à une balise de script spécifique de la collection de polices du thème. |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Retourne ou définit la police latine. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Retour :**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Retourne ou définit la police latine. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Retourne ou définit la police d'Asie orientale. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Retour :**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Retourne ou définit la police d'Asie orientale. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Retourne ou définit la police de script complexe. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Retour :**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Retourne ou définit la police de script complexe. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Retourne un dictionnaire de toutes les définitions de polices de script dans la présentation.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Gets the font name associated with a specific script tag from the presentation theme.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | The BCP-47 script code (e.g., "Latn", "Cyrl", "Jpan") used to identify a writing system. |

**Returns:**
java.lang.String - The name of the font used for the specified script, or  null  if the script is not defined.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | The BCP-47 script code (e.g., "Arab", "Hebr", "Hans") identifying the writing system. |
| fontName | java.lang.String | The name of the font to assign to the specified script. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)

Supprime le paramètre de police associé à une balise de script spécifique de la collection de polices du thème.

--------------------

> ```
> Cet exemple montre comment supprimer le mapping de police pour le script hébreu :
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| script | java.lang.String | Le code de script BCP-47 dont le paramètre de police doit être supprimé. |