---
title: Fonts
second_title: Aspose.Slides för Android via Java API-referens
description: Teckensnittssamling.
type: docs
url: /sv/com.aspose.slides/fonts/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Teckensnittssamling.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Returnerar en ordbok med alla skriptteckensnittdefinitioner i presentationen. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Hämtar teckensnittsnamnet som är associerat med en specifik skripttagg från presentationens tema. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Tilldelar ett teckensnittsnamn till en specifik skripttagg, vilket definierar hur text för det skriptet kommer att renderas i presentationen. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Tar bort teckensnittinställningen som är associerad med en specifik skripttagg från temats teckensnittssamling. |
| [getLatinFont()](#getLatinFont--) | Returnerar eller anger det latinska teckensnittet. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returnerar eller anger det latinska teckensnittet. |
| [getEastAsianFont()](#getEastAsianFont--) | Returnerar eller anger det östasiatiska teckensnittet. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returnerar eller anger det östasiatiska teckensnittet. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returnerar eller anger det komplexa skriptteckensnittet. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returnerar eller anger det komplexa skriptteckensnittet. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Returnerar en ordbok med alla skriptteckensnittdefinitioner i presentationen.

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
public final String getScriptFont(String script)
```

Hämtar teckensnittsnamnet som är associerat med en specifik skripttagg från presentationens tema.

--------------------

> ```
> Detta exempel visar hur man hämtar teckensnittet som tilldelats det kyrilliska skriptet i presentationens tema.
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
public final void setScriptFont(String script, String fontName)
```

Tilldelar ett teckensnittsnamn till en specifik skripttagg, vilket definierar hur text för det skriptet kommer att renderas i presentationen.

--------------------

> ```
> Detta exempel visar hur man sätter teckensnittet för det arabiska skriptet till "Segoe UI":
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
public final void removeScriptFont(String script)
```

Tar bort teckensnittinställningen som är associerad med en specifik skripttagg från temats teckensnittssamling.

--------------------

> ```
> Detta exempel demonstrerar hur man tar bort teckensnittsavbildningen för det hebreiska skriptet:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | java.lang.String | BCP-47 skriptkoden vars teckensnittinställning ska tas bort. |
### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Returnerar eller anger det latinska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Returnerar eller anger det latinska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Returnerar eller anger det östasiatiska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Returnerar eller anger det östasiatiska teckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Returnerar eller anger det komplexa skriptteckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Returnerar eller anger det komplexa skriptteckensnittet. Läs/skriv [IFontData](../../com.aspose.slides/ifontdata).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |