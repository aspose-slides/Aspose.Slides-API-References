---
title: IPropertyEffect
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje chování efektu vlastnosti.
type: docs
url: /cs/com.aspose.slides/ipropertyeffect/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

Reprezentuje chování vlastnosti efektu.
## Metody

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Určuje počáteční hodnotu animace. |
| [setFrom(String value)](#setFrom-java.lang.String-) | Určuje počáteční hodnotu animace. |
| [getTo()](#getTo--) | Určuje koncovou hodnotu animace. |
| [setTo(String value)](#setTo-java.lang.String-) | Určuje koncovou hodnotu animace. |
| [getBy()](#getBy--) | Určuje relativní posunovou hodnotu animace vzhledem k její pozici před zahájením animace. |
| [setBy(String value)](#setBy-java.lang.String-) | Určuje relativní posunovou hodnotu animace vzhledem k její pozici před zahájením animace. |
| [getValueType()](#getValueType--) | Určuje typ hodnoty vlastnosti. |
| [setValueType(int value)](#setValueType-int-) | Určuje typ hodnoty vlastnosti. |
| [getCalcMode()](#getCalcMode--) | Určuje režim interpolace pro animaci Čtení/Zápis [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | Určuje režim interpolace pro animaci Čtení/Zápis [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | Určuje body animace. |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | Určuje body animace. |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

Určuje počáteční hodnotu animace. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

Určuje počáteční hodnotu animace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTo() {#getTo--}
```
public abstract String getTo()
```

Určuje koncovou hodnotu animace. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

Určuje koncovou hodnotu animace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getBy() {#getBy--}
```
public abstract String getBy()
```

Určuje relativní posunovou hodnotu animace vzhledem k její pozici před zahájením animace. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

Určuje relativní posunovou hodnotu animace vzhledem k její pozici před zahájením animace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Určuje typ hodnoty vlastnosti. Čtení/Zápis [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Vrací:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Určuje typ hodnoty vlastnosti. Čtení/Zápis [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

Určuje režim interpolace pro animaci Čtení/Zápis [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Vrací:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

Určuje režim interpolace pro animaci Čtení/Zápis [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

Určuje body animace. Čtení/Zápis [IPointCollection](../../com.aspose.slides/ipointcollection).

**Vrací:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

Určuje body animace. Čtení/Zápis [IPointCollection](../../com.aspose.slides/ipointcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |