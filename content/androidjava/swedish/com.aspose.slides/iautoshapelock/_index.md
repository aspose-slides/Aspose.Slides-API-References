---
title: IAutoShapeLock
second_title: Aspose.Slides för Android via Java API-referens
description: Bestämmer vilka operationer som är inaktiverade på den överordnade AutoshapeEx.
type: docs
url: /sv/com.aspose.slides/iautoshapelock/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IAutoShapeLock extends IBaseShapeLock
```

Bestämmer vilka operationer som är inaktiverade på den överordnade AutoshapeEx.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Bestämmer om det är förbjudet att lägga till den här formen i en grupp. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Bestämmer om det är förbjudet att lägga till den här formen i en grupp. |
| [getSelectLocked()](#getSelectLocked--) | Bestämmer om det är förbjudet att markera den här formen. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Bestämmer om det är förbjudet att markera den här formen. |
| [getRotateLocked()](#getRotateLocked--) | Bestämmer om det är förbjudet att ändra rotationsvinkeln för den här formen. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Bestämmer om det är förbjudet att ändra rotationsvinkeln för den här formen. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Bestämmer om en form måste behålla bildförhållandet vid storleksändring. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Bestämmer om en form måste behålla bildförhållandet vid storleksändring. |
| [getPositionLocked()](#getPositionLocked--) | Bestämmer om det är förbjudet att flytta den här formen. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | Bestämmer om det är förbjudet att flytta den här formen. |
| [getSizeLocked()](#getSizeLocked--) | Bestämmer om det är förbjudet att ändra storlek på den här formen. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Bestämmer om det är förbjudet att ändra storlek på den här formen. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Bestämmer om det är förbjudet att direkt ändra konturen på den här formen. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Bestämmer om det är förbjudet att direkt ändra konturen på den här formen. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Bestämmer om det är förbjudet att ändra justeringsvärden. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Bestämmer om det är förbjudet att ändra justeringsvärden. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Bestämmer om det är förbjudet att ändra pilhuvuden. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Bestämmer om det är förbjudet att ändra pilhuvuden. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Bestämmer om det är förbjudet att ändra formtypen. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Bestämmer om det är förbjudet att ändra formtypen. |
| [getTextLocked()](#getTextLocked--) | Bestämmer om det är förbjudet att redigera text. |
| [setTextLocked(boolean value)](#setTextLocked-boolean-) | Bestämmer om det är förbjudet att redigera text. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Bestämmer om det är förbjudet att lägga till den här formen i en grupp. Läs-skriv boolesk.

**Returnerar:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Bestämmer om det är förbjudet att lägga till den här formen i en grupp. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Bestämmer om det är förbjudet att markera den här formen. Läs-skriv boolesk.

**Returnerar:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Bestämmer om det är förbjudet att markera den här formen. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Bestämmer om det är förbjudet att ändra rotationsvinkeln för den här formen. Läs-skriv boolesk.

**Returnerar:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Bestämmer om det är förbjudet att ändra rotationsvinkeln för den här formen. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Bestämmer om en form måste behålla bildförhållandet vid storleksändring. Läs-skriv boolesk.

**Returnerar:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Bestämmer om en form måste behålla bildförhållandet vid storleksändring. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

Bestämmer om det är förbjudet att flytta den här formen. Läs-skriv boolesk.

**Returnerar:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

Bestämmer om det är förbjudet att flytta den här formen. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Bestämmer om det är förbjudet att ändra storlek på den här formen. Läs-skriv boolesk.

**Returnerar:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Bestämmer om det är förbjudet att ändra storlek på den här formen. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Bestämmer om det är förbjudet att direkt ändra konturen på den här formen. Läs-skriv boolesk.

**Returnerar:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Bestämmer om det är förbjudet att direkt ändra konturen på den här formen. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Bestämmer om det är förbjudet att ändra justeringsvärden. Läs-skriv boolesk.

**Returnerar:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Bestämmer om det är förbjudet att ändra justeringsvärden. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Bestämmer om det är förbjudet att ändra pilhuvuden. Läs-skriv boolesk.

**Returnerar:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Bestämmer om det är förbjudet att ändra pilhuvuden. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Bestämmer om det är förbjudet att ändra formtypen. Läs-skriv boolesk.

**Returnerar:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Bestämmer om det är förbjudet att ändra formtypen. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTextLocked() {#getTextLocked--}
```
public abstract boolean getTextLocked()
```

Bestämmer om det är förbjudet att redigera text. Läs-skriv boolesk.

**Returnerar:**
boolean
### setTextLocked(boolean value) {#setTextLocked-boolean-}
```
public abstract void setTextLocked(boolean value)
```

Bestämmer om det är förbjudet att redigera text. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |