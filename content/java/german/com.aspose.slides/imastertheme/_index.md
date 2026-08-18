---
title: IMasterTheme
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein Master-Thema dar.
type: docs
url: /de/com.aspose.slides/imastertheme/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Stellt ein Master-Thema dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Gibt die Sammlung zusätzlicher Farbschemata zurück. |
| [getName()](#getName--) | Gibt den Namen eines Themas zurück. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen eines Themas zurück. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Gibt die Sammlung zusätzlicher Farbschemata zurück. Diese Schemata beeinflussen das Aussehen der Präsentation nicht, sie können als Hauptfarbschema für eine Folie ausgewählt werden. Nur lesbar [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Rückgabewert:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen eines Themas zurück. Lese-/Schreib-String.

**Rückgabewert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Gibt den Namen eines Themas zurück. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |