---
title: IMotionPath
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά τη διαδρομή κίνησης.
type: docs
url: /el/com.aspose.slides/imotionpath/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Αναπαριστά τη διαδρομή κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Προσθέτει νέα εντολή στο μονοπάτι |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των μονοπατιών στη συλλογή. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Εισάγει νέα εντολή στο μονοπάτι |
| [clear()](#clear--) | Αφαιρεί όλες τις εντολές από τη συλλογή. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Αφαιρεί τις καθορισμένες εντολές από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί μια εντολή στον καθορισμένο δείκτη. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια εντολή στον καθορισμένο δείκτη. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Προσθέτει νέα εντολή στο μονοπάτι

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Τύπος εντολής για το animation motion effect behavior [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Πίνακας σημείων java.awt.geom.Point2D.Float[] |
| ptsType | int | Τύπος σημείων στη διαδρομή κίνησης animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Δείχνει αν χρησιμοποιούνται σχετικές συντεταγμένες ή όχι boolean |

**Τιμή επιστροφής:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Εντολή ενός μονοπατιού [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Επιστρέφει τον αριθμό των μονοπατιών στη συλλογή. Μόνο για ανάγνωση int.

**Τιμή επιστροφής:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Εισάγει νέα εντολή στο μονοπάτι

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης για εισαγωγή εντολής int |
| type | int | Τύπος εντολής για το animation motion effect behavior [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Πίνακας σημείων java.awt.geom.Point2D.Float[] |
| ptsType | int | Τύπος σημείων στη διαδρομή κίνησης animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Δείχνει αν χρησιμοποιούνται σχετικές συντεταγμένες ή όχι boolean |
### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλες τις εντολές από τη συλλογή.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Αφαιρεί τις καθορισμένες εντολές από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Διαδρομή κίνησης προς αφαίρεση [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί μια εντολή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης για αφαίρεση εντολής int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Επιστρέφει μια εντολή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |
**Τιμή επιστροφής:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Εντολή στον καθορισμένο δείκτη [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)