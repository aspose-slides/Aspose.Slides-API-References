---
title: FontData
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt eine Schriftartdefinition dar.
type: docs
url: /de/com.aspose.slides/fontdata/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Stellt eine Schriftartdefinition dar. Unveränderlich.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Erstellt ein neues FontData-Objekt mit dem angegebenen Schriftartnamen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontName()](#getFontName--) | Gibt den Schriftartnamen zurück. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Gibt den Schriftartnamen zurück und ersetzt die Themenreferenz durch die tatsächlich verwendete Schriftart. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob zwei FontData-Instanzen gleich sind. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ und ist geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle. |
| [toString()](#toString--) | Gibt die String-Darstellung zurück. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Erstellt ein neues FontData-Objekt mit dem angegebenen Schriftartnamen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Name der Schriftart. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Gibt den Schriftartnamen zurück. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Gibt den Schriftartnamen zurück und ersetzt die Themenreferenz durch die tatsächlich verwendete Schriftart.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thema, aus dem der thematische Schriftartname entnommen werden soll. Es liegt in der Verantwortung des Aufrufers, einen korrekten Wert bereitzustellen. Siehe [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Rückgabe:**
java.lang.String - Schriftartname.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob zwei FontData-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das FontData, das mit dem aktuellen FontData verglichen werden soll. |

**Rückgabe:**
boolean - **true**, wenn das angegebene FontData dem aktuellen FontData entspricht; andernfalls **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ und ist geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle.

**Rückgabe:**
int - Hashcode des FontData.
### toString() {#toString--}
```
public String toString()
```

Gibt die String-Darstellung zurück.

**Rückgabe:**
java.lang.String - String-Darstellung.