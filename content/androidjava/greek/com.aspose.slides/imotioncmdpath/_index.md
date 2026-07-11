---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά μία εντολή ενός μονοπατιού.
type: docs
url: /el/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Αναπαριστά μία εντολή ενός μονοπατιού.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPoints()](#getPoints--) | Καθορίζει σημεία της εντολής. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Καθορίζει σημεία της εντολής. |
| [getCommandType()](#getCommandType--) | Καθορίζει τον τύπο της εντολής. |
| [setCommandType(int value)](#setCommandType-int-) | Καθορίζει τον τύπο της εντολής. |
| [isRelative()](#isRelative--) | Καθορίζει αν οι συντεταγμένες της εντολής είναι σχετικές ή όχι. |
| [setRelative(boolean value)](#setRelative-boolean-) | Καθορίζει αν οι συντεταγμένες της εντολής είναι σχετικές ή όχι. |
| [getPointsType()](#getPointsType--) | Καθορίζει τον τύπο των σημείων εντολής Ανάγνωση/εγγραφή [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Καθορίζει τον τύπο των σημείων εντολής Ανάγνωση/εγγραφή [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Καθορίζει σημεία της εντολής. Ανάγνωση/εγγραφή android.graphics.PointF[].

**Επιστρέφει:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```


Καθορίζει σημεία της εντολής. Ανάγνωση/εγγραφή android.graphics.PointF[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


Καθορίζει τον τύπο της εντολής. Ανάγνωση/εγγραφή [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Επιστρέφει:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


Καθορίζει τον τύπο της εντολής. Ανάγνωση/εγγραφή [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```


Καθορίζει αν οι συντεταγμένες της εντολής είναι σχετικές ή όχι. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```


Καθορίζει αν οι συντεταγμένες της εντολής είναι σχετικές ή όχι. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```


Καθορίζει τον τύπο των σημείων εντολής Ανάγνωση/εγγραφή [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Επιστρέφει:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


Καθορίζει τον τύπο των σημείων εντολής Ανάγνωση/εγγραφή [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |