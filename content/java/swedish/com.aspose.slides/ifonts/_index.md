---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /sv/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Representerar typsnittssamling.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Returnerar eller anger det latinska typsnittet. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returnerar eller anger det latinska typsnittet. |
| [getEastAsianFont()](#getEastAsianFont--) | Returnerar eller anger det östasiatiska typsnittet. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returnerar eller anger det östasiatiska typsnittet. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returnerar eller anger det komplexa skripttypsnittet. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returnerar eller anger det komplexa skripttypsnittet. |
| [getScriptFontMap()](#getScriptFontMap--) | Returnerar en ordbok med alla skripttypsnittsdefinitioner i presentationen. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Hämtar typsnittsnamnet som är associerat med en specifik skripttagg från presentationens tema. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Tilldelar ett typsnittsnamn till en specifik skripttagg, som definierar hur text i det skriptet renderas i presentationen. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Tar bort typsnittsinställningen som är associerad med en specifik skripttagg från temats typsnittssamling. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Returnerar eller anger det latinska typsnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Returnerar eller anger det latinska typsnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Returnerar eller anger det östasiatiska typsnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Returnerar eller anger det östasiatiska typsnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Returnerar eller anger det komplexa skripttypsnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Returnerar eller anger det komplexa skripttypsnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Returnerar en ordbok med alla skripttypsnittsdefinitioner i presentationen.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Returnerar:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - En ordbok som mappar skriptkoder till typsnittsnamn.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


Hämtar typsnittsnamnet som är associerat med en specifik skripttagg från presentationens tema.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | java.lang.String | BCP-47 skriptkoden (t.ex. "Latn", "Cyrl", "Jpan") som används för att identifiera ett skriftsystem. |

**Returnerar:**
java.lang.String - Namnet på typsnittet som används för det angivna skriptet, eller  null  om skriptet inte är definierat.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


Tilldelar ett typsnittsnamn till en specifik skripttagg, som definierar hur text i det skriptet renderas i presentationen.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | java.lang.String | BCP-47 skriptkoden (t.ex. "Arab", "Hebr", "Hans") som identifierar skriftsystemet. |
| fontName | java.lang.String | Namnet på typsnittet som ska tilldelas den angivna skripttaggen. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


Tar bort typsnittsinställningen som är associerad med en specifik skripttagg från temats typsnittssamling.

--------------------

> ```
> Det här exemplet visar hur man tar bort teckensnittsmappningen för det hebreiska skriptet:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | java.lang.String | BCP-47 skriptkoden vars typsnittsinställning ska tas bort. |