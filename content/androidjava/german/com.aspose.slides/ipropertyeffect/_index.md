---
title: IPropertyEffect
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt das Verhalten des Property-Effekts dar.
type: docs
url: /de/com.aspose.slides/ipropertyeffect/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

Stellt das Verhalten des Property-Effekts dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrom()](#getFrom--) | Gibt den Startwert der Animation an. |
| [setFrom(String value)](#setFrom-java.lang.String-) | Gibt den Startwert der Animation an. |
| [getTo()](#getTo--) | Gibt den Endwert für die Animation an. |
| [setTo(String value)](#setTo-java.lang.String-) | Gibt den Endwert für die Animation an. |
| [getBy()](#getBy--) | Gibt einen relativen Versatzwert für die Animation relativ zu ihrer Position vor Beginn der Animation an. |
| [setBy(String value)](#setBy-java.lang.String-) | Gibt einen relativen Versatzwert für die Animation relativ zu ihrer Position vor Beginn der Animation an. |
| [getValueType()](#getValueType--) | Gibt den Typ eines Property-Werts an. |
| [setValueType(int value)](#setValueType-int-) | Gibt den Typ eines Property-Werts an. |
| [getCalcMode()](#getCalcMode--) | Gibt den Interpolationsmodus für die Animation an. Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | Gibt den Interpolationsmodus für die Animation an. Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | Gibt die Punkte der Animation an. |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | Gibt die Punkte der Animation an. |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

Gibt den Startwert der Animation an. Read/write String.

**Rückgabewert:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

Gibt den Startwert der Animation an. Read/write String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTo() {#getTo--}
```
public abstract String getTo()
```

Gibt den Endwert für die Animation an. Read/write String.

**Rückgabewert:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

Gibt den Endwert für die Animation an. Read/write String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getBy() {#getBy--}
```
public abstract String getBy()
```

Gibt einen relativen Versatzwert für die Animation relativ zu ihrer Position vor Beginn der Animation an. Read/write String.

**Rückgabewert:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

Gibt einen relativen Versatzwert für die Animation relativ zu ihrer Position vor Beginn der Animation an. Read/write String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Gibt den Typ eines Property-Werts an. Read/write [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Rückgabewert:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Gibt den Typ eines Property-Werts an. Read/write [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

Gibt den Interpolationsmodus für die Animation an. Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Rückgabewert:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

Gibt den Interpolationsmodus für die Animation an. Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

Gibt die Punkte der Animation an. Read/write [IPointCollection](../../com.aspose.slides/ipointcollection).

**Rückgabewert:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

Gibt die Punkte der Animation an. Read/write [IPointCollection](../../com.aspose.slides/ipointcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |