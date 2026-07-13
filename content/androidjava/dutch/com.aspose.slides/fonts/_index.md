---
title: Fonts
second_title: Aspose.Slides voor Android via Java API-referentie
description: Lettertypecollectie.
type: docs
url: /nl/com.aspose.slides/fonts/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Lettertypecollectie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Retourneert een woordenboek met alle scriptlettertype-definities in de presentatie. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Haalt de naam van het lettertype op die aan een specifiek script-tag is gekoppeld vanuit het presentatiethema. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Kent een lettertype-naam toe aan een specifiek script-tag, waarmee wordt bepaald hoe tekst van dat script in de presentatie wordt weergegeven. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Verwijdert de lettertype-instelling die aan een specifiek script-tag is gekoppeld uit de lettertype-collectie van het thema. |
| [getLatinFont()](#getLatinFont--) | Retourneert of stelt het Latijnse lettertype in. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Retourneert of stelt het Latijnse lettertype in. |
| [getEastAsianFont()](#getEastAsianFont--) | Retourneert of stelt het Oost-Aziatische lettertype in. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Retourneert of stelt het Oost-Aziatische lettertype in. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retourneert of stelt het complexe script-lettertype in. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Retourneert of stelt het complexe script-lettertype in. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Retourneert een woordenboek met alle scriptlettertype-definities in de presentatie.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Retour:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Een woordenboek dat scriptcodes koppelt aan lettertype-namen.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Haalt de naam van het lettertype op die aan een specifiek script-tag is gekoppeld vanuit het presentatiethema.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | java.lang.String | De BCP-47 scriptcode (bijv. "Latn", "Cyrl", "Jpan") die wordt gebruikt om een schrijfsysteem te identificeren. |

**Retour:**
java.lang.String - De naam van het lettertype dat voor het opgegeven script wordt gebruikt, of  null  als het script niet is gedefinieerd.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Kent een lettertype-naam toe aan een specifiek script-tag, waarmee wordt bepaald hoe tekst van dat script in de presentatie wordt weergegeven.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | java.lang.String | De BCP-47 scriptcode (bijv. "Arab", "Hebr", "Hans") die het schrijfsysteem identificeert. |
| fontName | java.lang.String | De naam van het lettertype dat aan het opgegeven script moet worden toegewezen. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Verwijdert de lettertype-instelling die aan een specifiek script-tag is gekoppeld uit de lettertype-collectie van het thema.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | java.lang.String | De BCP-47 scriptcode waarvan de lettertype-instelling moet worden verwijderd. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Retourneert of stelt het Latijnse lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Retourneert of stelt het Latijnse lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Retourneert of stelt het Oost-Aziatische lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Retourneert of stelt het Oost-Aziatische lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Retourneert of stelt het complexe script-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Retourneert of stelt het complexe script-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |