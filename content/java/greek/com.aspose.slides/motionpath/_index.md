---
title: MotionPath
second_title: Aspose.Slides για την αναφορά API της Java
description: Αντιπροσωπεύει τη διαδρομή κίνησης.
type: docs
url: /el/com.aspose.slides/motionpath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Αντιπροσωπεύει τη διαδρομή κίνησης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Προσθέτει νέα εντολή στη διαδρομή |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των διαδρομών στη συλλογή. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Εισάγει νέα εντολή στη διαδρομή |
| [clear()](#clear--) | Αφαιρεί όλες τις εντολές από τη συλλογή. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Αφαιρεί τις συγκεκριμένες εντολές από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί μια εντολή στον καθορισμένο δείκτη. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια εντολή στον καθορισμένο δείκτη. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Προσθέτει νέα εντολή στη διαδρομή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Array of points |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relative coordinates boolean |

**Επιστρέφει:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Επιστρέφει τον αριθμό των διαδρομών στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Εισάγει νέα εντολή στη διαδρομή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | The zero-based index at which item should be inserted. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Array of points |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relative coordinates boolean |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλες τις εντολές από τη συλλογή.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Αφαιρεί τις συγκεκριμένες εντολές από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Motion path to remove. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί μια εντολή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Index of a command that should be deleted. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Επιστρέφει μια εντολή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Index of element. |

**Επιστρέφει:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Το αντικείμενο [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - An java.util.Iterator for the entire collection.