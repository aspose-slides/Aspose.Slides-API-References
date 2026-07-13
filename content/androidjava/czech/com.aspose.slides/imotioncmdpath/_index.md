---
title: IMotionCmdPath
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje jeden příkaz cesty.
type: docs
url: /cs/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Reprezentuje jeden příkaz cesty.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPoints()](#getPoints--) | Určuje body příkazu. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Určuje body příkazu. |
| [getCommandType()](#getCommandType--) | Určuje body příkazu. |
| [setCommandType(int value)](#setCommandType-int-) | Určuje body příkazu. |
| [isRelative()](#isRelative--) | Určuje, zda jsou souřadnice příkazu relativní či nikoli. |
| [setRelative(boolean value)](#setRelative-boolean-) | Určuje, zda jsou souřadnice příkazu relativní či nikoli. |
| [getPointsType()](#getPointsType--) | Určuje typ bodů příkazu Čtení/Zápis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Určuje typ bodů příkazu Čtení/Zápis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Určuje body příkazu. Čtení/Zápis android.graphics.PointF[].

**Vrací:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```


Určuje body příkazu. Čtení/Zápis android.graphics.PointF[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |
### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


Určuje typ příkazu. Čtení/Zápis [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Vrací:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


Určuje typ příkazu. Čtení/Zápis [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```


Určuje, zda jsou souřadnice příkazu relativní či nikoli. Čtení/Zápis boolean.

**Vrací:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```


Určuje, zda jsou souřadnice příkazu relativní či nikoli. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```


Určuje typ bodů příkazu Čtení/Zápis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Vrací:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


Určuje typ bodů příkazu Čtení/Zápis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |