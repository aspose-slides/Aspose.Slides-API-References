---
title: IMotionCmdPath
second_title: Aspose.Slides for Java API Reference
description: Represent one command of a path.
type: docs
url: /de/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Stellt einen Befehl eines Pfads dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPoints()](#getPoints--) | Specifies points of command. |
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | Specifies points of command. |
| [getCommandType()](#getCommandType--) | Specifies command type. |
| [setCommandType(int value)](#setCommandType-int-) | Specifies command type. |
| [isRelative()](#isRelative--) | Determine command coordinates relative or not. |
| [setRelative(boolean value)](#setRelative-boolean-) | Determine command coordinates relative or not. |
| [getPointsType()](#getPointsType--) | Specifies command points type Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Specifies command points type Read/write [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |

### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

Spezifiziert die Punkte des Befehls. Lesen/Schreiben java.awt.geom.Point2D.Float[].

**Rückgabe:**
java.awt.geom.Point2D.Float[]

### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```

Spezifiziert die Punkte des Befehls. Lesen/Schreiben java.awt.geom.Point2D.Float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Spezifiziert den Befehlstyp. Lesen/Schreiben [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Rückgabe:**
int

### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Spezifiziert den Befehlstyp. Lesen/Schreiben [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Bestimmt, ob die Befehlskoordinaten relativ sind oder nicht. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Bestimmt, ob die Befehlskoordinaten relativ sind oder nicht. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Spezifiziert den Typ der Befehlspunkte. Lesen/Schreiben [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Rückgabe:**
int

### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Spezifiziert den Typ der Befehlspunkte. Lesen/Schreiben [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |