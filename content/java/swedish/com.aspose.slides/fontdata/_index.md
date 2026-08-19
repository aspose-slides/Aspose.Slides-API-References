---
title: FontData
second_title: Aspose.Slides för Java API-referens
description: Representerar en typsnittsdefinition.
type: docs
url: /sv/com.aspose.slides/fontdata/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Representerar en typsnittsdefinition. Oföränderlig.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Skapar ett nytt FontData-objekt med det angivna typsnittsnamnet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontName()](#getFontName--) | Returnerar typsnittsnamnet. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returnerar typsnittsnamnet och ersätter temareferens med ett faktiskt använt typsnitt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om två FontData-instanser är lika. |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ, lämplig för användning i hash-algoritmer och datastrukturer som en hash-tabell. |
| [toString()](#toString--) | Returnerar strängrepresentation. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Skapar ett nytt FontData-objekt med det angivna typsnittsnamnet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Typsnittsnamn. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Returnerar typsnittsnamnet. Läs/skriv String.

**Returnerar:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Returnerar typsnittsnamnet och ersätter temareferens med ett faktiskt använt typsnitt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema varifrån det tematiska typsnittsnamnet ska tas. Det är upp till anroparen att tillhandahålla ett korrekt värde. Se [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Returnerar:**
java.lang.String - Typsnittsnamn.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Avgör om två FontData-instanser är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | FontData att jämföra med den aktuella FontData. |

**Returnerar:**
boolean - **true** om den angivna FontData är lika med den aktuella FontData; annars **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hash-funktion för en viss typ, lämplig för användning i hash-algoritmer och datastrukturer som en hash-tabell.

**Returnerar:**
int - Hash-kod för FontData.
### toString() {#toString--}
```
public String toString()
```

Returnerar strängrepresentation.

**Returnerar:**
java.lang.String - Strängrepresentation.