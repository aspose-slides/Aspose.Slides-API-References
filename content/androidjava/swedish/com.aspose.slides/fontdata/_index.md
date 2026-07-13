---
title: FontData
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en teckensnittdefinition.
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

Representerar en teckensnittdefinition. Oföränderlig.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Skapar ett nytt FontData-objekt med det angivna teckensnittsnamnet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontName()](#getFontName--) | Returnerar teckensnittsnamnet. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returnerar teckensnittsnamnet, ersätter temareferens med ett faktiskt använt teckensnitt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om två FontData-instansers är lika. |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ, lämplig för användning i hashalgoritmer och datastrukturer som en hash-tabell. |
| [toString()](#toString--) | Returnerar strängrepresentation. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Skapar ett nytt FontData-objekt med det angivna teckensnittsnamnet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Teckensnittsnamn. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Returnerar teckensnittsnamnet. Läs/skriv String.

**Returnerar:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Returnerar teckensnittsnamnet, ersätter temareferens med ett faktiskt använt teckensnitt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema från vilket tematiskt teckensnittsnamn ska tas. Det är upp till anroparen att tillhandahålla ett korrekt värde. Se [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Returnerar:**
java.lang.String - Teckensnittsnamn.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om två FontData-instansers är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | FontData som ska jämföras med den aktuella FontData. |

**Returnerar:**
boolean - **true** om den angivna FontData är lika med den aktuella FontData; annars, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hashfunktion för en viss typ, lämplig för användning i hashalgoritmer och datastrukturer som en hash-tabell.

**Returnerar:**
int - Hashkod för FontData.
### toString() {#toString--}
```
public String toString()
```

Returnerar strängrepresentation.

**Returnerar:**
java.lang.String - Strängrepresentation.