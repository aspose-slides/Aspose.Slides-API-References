---
title: FontData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een lettertype-definitie voor.
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

Stelt een lettertype-definitie voor. Onveranderlijk.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Maakt een nieuw FontData-object met de opgegeven lettertype-naam. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontName()](#getFontName--) | Retourneert de naam van het lettertype. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Retourneert de naam van het lettertype, waarbij een themareferentie wordt vervangen door een daadwerkelijk gebruikt lettertype. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of twee FontData-instanties gelijk zijn. |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hash-tabel. |
| [toString()](#toString--) | Retourneert de tekenreeksrepresentatie. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Maakt een nieuw FontData-object met de opgegeven lettertype-naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het lettertype. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Retourneert de naam van het lettertype. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Retourneert de naam van het lettertype, waarbij een themareferentie wordt vervangen door een daadwerkelijk gebruikt lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thema waaruit de gethematiseerde lettertype-naam moet worden gehaald. Het is aan de aanroeper om een juiste waarde te leveren. Zie [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

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

Dient als hash-functie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hash-tabel.

**Retourneert:**
int - Hash-code van de FontData.
### toString() {#toString--}
```
public String toString()
```

Retourneert een tekenreeksrepresentatie.

**Retourneert:**
java.lang.String - String-representatie.