---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /de/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Stellt Zugriff auf Aufwärts-/Abwärtsbalken von Linien- oder Aktien-Diagrammen bereit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Gibt das Format der Aufwärtsbalken zurück. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Gibt das Format der Abwärtsbalken zurück. |
| [hasUpDownBars()](#hasUpDownBars--) | Ermittelt, ob das Diagramm Aufwärts-/Abwärtsbalken hat. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Ermittelt, ob das Diagramm Aufwärts-/Abwärtsbalken hat. |
| [getGapWidth()](#getGapWidth--) | Gibt die Lückenbreite zurück oder setzt sie. |
| [setGapWidth(int value)](#setGapWidth-int-) | Gibt die Lückenbreite zurück oder setzt sie. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Gibt das Format der Aufwärtsbalken zurück. Nur lesbar [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Gibt das Format der Abwärtsbalken zurück. Nur lesbar [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Ermittelt, ob das Diagramm Aufwärts-/Abwärtsbalken hat. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Ermittelt, ob das Diagramm Aufwärts-/Abwärtsbalken hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Gibt die Lückenbreite zurück oder setzt sie. Lesen/Schreiben int.

**Rückgabe:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Gibt die Lückenbreite zurück oder setzt sie. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |