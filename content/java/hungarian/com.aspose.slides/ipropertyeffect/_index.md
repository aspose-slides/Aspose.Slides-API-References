---
title: IPropertyEffect
second_title: Aspose.Slides for Java API referencia
description: A tulajdonság hatásának viselkedését ábrázolja.
type: docs
url: /hu/com.aspose.slides/ipropertyeffect/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

A tulajdonság hatás viselkedését képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getFrom()](#getFrom--) | Megadja az animáció kezdőértékét. |
| [setFrom(String value)](#setFrom-java.lang.String-) | Megadja az animáció kezdőértékét. |
| [getTo()](#getTo--) | Megadja az animáció végértékét. |
| [setTo(String value)](#setTo-java.lang.String-) | Megadja az animáció végértékét. |
| [getBy()](#getBy--) | Megad egy relatív eltolási értéket az animációhoz a kezdés előtti pozícióhoz képest. |
| [setBy(String value)](#setBy-java.lang.String-) | Megad egy relatív eltolási értéket az animációhoz a kezdés előtti pozícióhoz képest. |
| [getValueType()](#getValueType--) | Megadja egy tulajdonság értékének típusát. |
| [setValueType(int value)](#setValueType-int-) | Megadja egy tulajdonság értékének típusát. |
| [getCalcMode()](#getCalcMode--) | Megadja az animáció interpolációs módját Olvasás/írás [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | Megadja az animáció interpolációs módját Olvasás/írás [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | Megadja az animáció pontjait. |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | Megadja az animáció pontjait. |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

Megadja az animáció kezdőértékét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

Megadja az animáció kezdőértékét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getTo() {#getTo--}
```
public abstract String getTo()
```

Megadja az animáció végértékét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

Megadja az animáció végértékét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getBy() {#getBy--}
```
public abstract String getBy()
```

Megad egy relatív eltolási értéket az animációhoz a kezdés előtti pozícióhoz képest. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

Megad egy relatív eltolási értéket az animációhoz a kezdés előtti pozícióhoz képest. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Megadja egy tulajdonság értékének típusát. Olvasás/írás [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Visszatér:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Megadja egy tulajdonság értékének típusát. Olvasás/írás [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

Megadja az animáció interpolációs módját Olvasás/írás [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Visszatér:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

Megadja az animáció interpolációs módját Olvasás/írás [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

Megadja az animáció pontjait. Olvasás/írás [IPointCollection](../../com.aspose.slides/ipointcollection).

**Visszatér:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

Megadja az animáció pontjait. Olvasás/írás [IPointCollection](../../com.aspose.slides/ipointcollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |