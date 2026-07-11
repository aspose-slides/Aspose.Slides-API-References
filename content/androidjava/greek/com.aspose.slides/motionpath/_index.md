---
title: MotionPath
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τη διαδρομή κίνησης.
type: docs
url: /el/com.aspose.slides/motionpath/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Αναπαριστά τη διαδρομή κίνησης.
## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Μέθοδοι

| Method | Description |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Προσθέτει νέα εντολή στη διαδρομή |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των διαδρομών στη συλλογή. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Εισάγει νέα εντολή στη διαδρομή |
| [clear()](#clear--) | Αφαιρεί όλες τις εντολές από τη συλλογή. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Αφαιρεί τις καθορισμένες εντολές από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί μια εντολή στο καθορισμένο ευρετήριο. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια εντολή στο καθορισμένο ευρετήριο. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διαπερνά τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Προσθέτει νέα εντολή στη διαδρομή

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Πίνακας σημείων |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Λογική τιμή για σχετικές συντεταγμένες |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Επιστρέφει τον αριθμό των διαδρομών στη συλλογή. Μόνο για ανάγνωση int.

**Returns:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Εισάγει νέα εντολή στη διαδρομή

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικό-βασισμένος δείκτης όπου θα εισαχθεί το στοιχείο. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Πίνακας σημείων |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Λογική τιμή για σχετικές συντεταγμένες |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλες τις εντολές από τη συλλογή.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Αφαιρεί τις καθορισμένες εντολές από τη συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Διαδρομή κίνησης προς αφαίρεση. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί μια εντολή στο καθορισμένο ευρετήριο.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης της εντολής που πρέπει να διαγραφεί. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Επιστρέφει μια εντολή στο καθορισμένο ευρετήριο.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Το αντικείμενο [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Επιστρέφει έναν enumerator που διαπερνά τη συλλογή.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.