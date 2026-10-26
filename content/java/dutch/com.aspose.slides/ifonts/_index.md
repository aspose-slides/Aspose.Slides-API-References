---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /nl/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Stelt een collectie lettertypen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Geeft of stelt het Latijnse lettertype in. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Geeft of stelt het Latijnse lettertype in. |
| [getEastAsianFont()](#getEastAsianFont--) | Geeft of stelt het Oost-Aziatische lettertype in. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Geeft of stelt het Oost-Aziatische lettertype in. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Geeft of stelt het complexe scriptlettertype in. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Geeft of stelt het complexe scriptlettertype in. |
| [getScriptFontMap()](#getScriptFontMap--) | Geeft een woordenboek van alle scriptlettertype-definities in de presentatie. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Haalt de lettertype-naam op die gekoppeld is aan een specifieke script-tag uit het presentatiethema. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Kent een lettertype-naam toe aan een specifieke script-tag, die bepaalt hoe tekst van dat script in de presentatie wordt weergegeven. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Verwijdert de lettertype-instelling die gekoppeld is aan een specifieke script-tag uit de lettertype-collectie van het thema. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Geeft of stelt het Latijnse lettertype in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Geeft of stelt het Latijnse lettertype in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Geeft of stelt het Oost-Aziatische lettertype in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Geeft of stelt het Oost-Aziatische lettertype in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Geeft of stelt het complexe scriptlettertype in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Retour:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Geeft of stelt het complexe scriptlettertype in. Lezen/Schrijven [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Geeft een woordenboek van alle scriptlettertype-definities in de presentatie.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Een woordenboek dat scriptcodes koppelt aan lettertypenamen.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


Haalt de lettertype-naam op die gekoppeld is aan een specifieke script-tag uit het presentatiethema.

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
java.lang.String - De naam van het lettertype dat wordt gebruikt voor het opgegeven script, of  null  als het script niet is gedefinieerd.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


Kent een lettertype-naam toe aan een specifieke script-tag, die bepaalt hoe tekst van dat script in de presentatie wordt weergegeven.

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
| fontName | java.lang.String | De naam van het lettertype dat moet worden toegewezen aan het opgegeven script. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


Verwijdert de lettertype-instelling die gekoppeld is aan een specifieke script-tag uit de lettertype-collectie van het thema.

--------------------

> ```
> Dit voorbeeld laat zien hoe u de lettertype-mapping voor het Hebreeuwse script verwijdert:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | java.lang.String | De BCP-47 scriptcode waarvan de lettertype-instelling moet worden verwijderd. |