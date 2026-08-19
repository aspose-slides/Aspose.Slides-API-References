---
title: FontData
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een lettertype-definitie.
type: docs
url: /nl/com.aspose.slides/fontdata/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Vertegenwoordigt een lettertype-definitie. Onveranderlijk.
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontName()](#getFontName--) | Geeft de naam van het lettertype terug. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Geeft de naam van het lettertype terug, waarbij de thema-referentie wordt vervangen door het daadwerkelijk gebruikte lettertype. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of twee FontData-instanties gelijk zijn. |
| [hashCode()](#hashCode--) | Dient als hashfunctie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel. |
| [toString()](#toString--) | Geeft de tekenreeksrepresentatie terug. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Maakt een nieuw FontData-object met de opgegeven lettertype-naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Lettertype-naam. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Geeft de naam van het lettertype terug. Lees/schrijf String.

**Retourneert:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Geeft de naam van het lettertype terug, waarbij de thema-referentie wordt vervangen door het daadwerkelijk gebruikte lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thema waaruit de thematische lettertype-naam moet worden genomen. Het is aan de aanroeper om een correcte waarde te leveren. Zie [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Retourneert:**
java.lang.String - Lettertype-naam.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of twee FontData-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De FontData om te vergelijken met de huidige FontData. |

**Retourneert:**
boolean - **true** als de opgegeven FontData gelijk is aan de huidige FontData; anders, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als hashfunctie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.

**Retourneert:**
int - Hash-code van de FontData.
### toString() {#toString--}
```
public String toString()
```

Geeft de tekenreeksrepresentatie terug.

**Retourneert:**
java.lang.String - Tekenreeksrepresentatie.