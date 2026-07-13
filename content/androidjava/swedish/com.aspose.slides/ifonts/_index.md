---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Represents fonts collection.
type: docs
url: /sv/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Representerar teckensnittssamling.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Returnerar eller anger det latinska teckensnittet. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returnerar eller anger det latinska teckensnittet. |
| [getEastAsianFont()](#getEastAsianFont--) | Returnerar eller anger det östasiatiska teckensnittet. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returnerar eller anger det östasiatiska teckensnittet. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returnerar eller anger det komplexa skriptteckensnittet. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returnerar eller anger det komplexa skriptteckensnittet. |
| [getScriptFontMap()](#getScriptFontMap--) | Returnerar en ordbok med alla skriptteckensnittsdefinitioner i presentationen. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Hämtar teckensnittsnamnet som är kopplat till en specifik skripttagg från presentationens tema. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Tilldelar ett teckensnittsnamn till en specifik skripttagg, vilket definierar hur text i det skriptet renderas i presentationen. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Tar bort teckensnittinställningen som är kopplad till en specifik skripttagg från temats teckensnittssamling. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Returnerar eller anger det latinska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Returnerar eller anger det latinska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Returnerar eller anger det östasiatiska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Returnerar eller anger det östasiatiska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Returnerar eller anger det komplexa skriptteckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Returnerar eller anger det komplexa skriptteckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Returnerar en ordbok med alla skriptteckensnittsdefinitioner i presentationen.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - En ordbok som mappar skriptkoder till teckensnittsnamn.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Hämtar teckensnittsnamnet som är kopplat till en specifik skripttagg från presentationens tema.

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
java.lang.String - Namnet på teckensnittet som används för det angivna skriptet, eller  null  om skriptet inte är definierat.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Tilldelar ett teckensnittsnamn till en specifik skripttagg, vilket definierar hur text i det skriptet renderas i presentationen.

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
| fontName | java.lang.String | Namnet på teckensnittet som ska tilldelas det angivna skriptet. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Tar bort teckensnittinställningen som är kopplad till en specifik skripttagg från temats teckensnittssamling.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | java.lang.String | BCP-47 skriptkoden vars teckensnittinställning ska tas bort. |