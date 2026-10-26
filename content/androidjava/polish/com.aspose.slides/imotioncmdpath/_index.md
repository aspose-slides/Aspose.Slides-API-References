---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje jedno polecenie ścieżki.
type: docs
url: /pl/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Reprezentuje jedno polecenie ścieżki.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPoints()](#getPoints--) | Określa punkty polecenia. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Określa punkty polecenia. |
| [getCommandType()](#getCommandType--) | Określa typ polecenia. |
| [setCommandType(int value)](#setCommandType-int-) | Określa typ polecenia. |
| [isRelative()](#isRelative--) | Określa, czy współrzędne polecenia są względne. |
| [setRelative(boolean value)](#setRelative-boolean-) | Określa, czy współrzędne polecenia są względne. |
| [getPointsType()](#getPointsType--) | Określa typ punktów polecenia Odczyt/zapis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Określa typ punktów polecenia Odczyt/zapis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

Określa punkty polecenia. Odczyt/zapis android.graphics.PointF[].

**Zwraca:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

Określa punkty polecenia. Odczyt/zapis android.graphics.PointF[].

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |
### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Określa typ polecenia. Odczyt/zapis [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Zwraca:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Określa typ polecenia. Odczyt/zapis [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Określa, czy współrzędne polecenia są względne. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Określa, czy współrzędne polecenia są względne. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Określa typ punktów polecenia Odczyt/zapis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Zwraca:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Określa typ punktów polecenia Odczyt/zapis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |