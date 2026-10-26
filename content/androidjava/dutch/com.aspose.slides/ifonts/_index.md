---
title: IFonts
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt fonts-collectie.
type: docs
url: /nl/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Vertegenwoordigt fonts-collectie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Retourneert of stelt het Latin-lettertype in. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Retourneert of stelt het Latin-lettertype in. |
| [getEastAsianFont()](#getEastAsianFont--) | Retourneert of stelt het East Asian-lettertype in. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Retourneert of stelt het East Asian-lettertype in. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Retourneert of stelt het complex script-lettertype in. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Retourneert of stelt het complex script-lettertype in. |
| [getScriptFontMap()](#getScriptFontMap--) | Retourneert een woordenboek van alle scriptlettertype-definities in de presentatie. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Haalt de lettertype-naam op die is gekoppeld aan een specifiek script-tag uit het thema van de presentatie. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Koppelt een lettertype-naam aan een specifiek script-tag, waarmee wordt bepaald hoe tekst van dat script in de presentatie wordt weergegeven. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Verwijdert de lettertype-instelling die is gekoppeld aan een specifiek script-tag uit de lettertype-collectie van het thema. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Retourneert of stelt het Latin-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Retourneert of stelt het Latin-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Retourneert of stelt het East Asian-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Retourneert of stelt het East Asian-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Retourneert of stelt het complex script-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Retourneert of stelt het complex script-lettertype in. Lezen/schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Retourneert een woordenboek van alle scriptlettertype-definities in de presentatie.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Een woordenboek dat script-codes koppelt aan lettertype-namen.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Haalt de lettertype-naam op die is gekoppeld aan een specifiek script-tag uit het thema van de presentatie.

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
| script | java.lang.String | De BCP-47 script-code (bijv. "Latn", "Cyrl", "Jpan") die wordt gebruikt om een schrijfsysteem te identificeren. |

**Retour:**
java.lang.String - De naam van het lettertype dat wordt gebruikt voor het opgegeven script, of  null  als het script niet gedefinieerd is.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Koppelt een lettertype-naam aan een specifiek script-tag, waarmee wordt bepaald hoe tekst van dat script in de presentatie wordt weergegeven.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | java.lang.String | De BCP-47 script-code (bijv. "Arab", "Hebr", "Hans") die het schrijfsysteem identificeert. |
| fontName | java.lang.String | De naam van het lettertype dat moet worden toegewezen aan het opgegeven script. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Verwijdert de lettertype-instelling die is gekoppeld aan een specifiek script-tag uit de lettertype-collectie van het thema.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | java.lang.String | De BCP-47 script-code waarvan de lettertype-instelling moet worden verwijderd. |