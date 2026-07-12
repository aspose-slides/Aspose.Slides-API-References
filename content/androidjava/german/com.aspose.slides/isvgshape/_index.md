---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options for SVG shape.
type: docs
url: /de/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Stellt Optionen für SVG shape dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Legt den Ereignishandler für das Shape fest |
| [getId()](#getId--) | Setzt oder liest die ID für das Shape |
| [setId(String value)](#setId-java.lang.String-) | Setzt oder liest die ID für das Shape |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


Legt den Ereignishandler für das Shape fest

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | int | Typ des Ereignisses. |
| handler | java.lang.String | JavaScript-Funktion zur Behandlung des Ereignisses. Nullwert entfernt den Handler. |

### getId() {#getId--}
```
public abstract String getId()
```


Setzt oder liest die ID für das Shape

**Rückgabewert:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Setzt oder liest die ID für das Shape

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |