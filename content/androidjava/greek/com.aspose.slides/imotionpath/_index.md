---
title: IMotionPath
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει τη διαδρομή κίνησης.
type: docs
url: /el/com.aspose.slides/imotionpath/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath)
```

Αντιπροσωπεύει τη διαδρομή κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Προσθέτει νέα εντολή στη διαδρομή |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των διαδρομών στη συλλογή. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Εισάγει νέα εντολή στη διαδρομή |
| [clear()](#clear--) | Αφαιρεί όλες τις εντολές από τη συλλογή. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Αφαιρεί τις καθορισμένες εντολές από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί μια εντολή στον καθορισμένο δείκτη. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια εντολή στον καθορισμένο δείκτη. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Προσθέτει νέα εντολή στη διαδρομή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Τύπος εντολής για τη συμπεριφορά εφέ κίνησης [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Πίνακας σημείων android.graphics.PointF[] |
| ptsType | int | Τύπος σημείων στη διαδρομή κίνησης [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Δείχνει αν χρησιμοποιούνται σχετικές συντεταγμένες ή όχι boolean |

**Επιστρέφει:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Εντολή μιας διαδρομής [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Επιστρέφει τον αριθμό των διαδρομών στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Εισάγει νέα εντολή στη διαδρομή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης για την εισαγωγή εντολής int |
| type | int | Τύπος εντολής για τη συμπεριφορά εφέ κίνησης [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Πίνακας σημείων android.graphics.PointF[] |
| ptsType | int | Τύπος σημείων στη διαδρομή κίνησης [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
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
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Διαδρομή κίνησης για αφαίρεση [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

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

**Επιστρέφει:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Εντολή στον καθορισμένο δείκτη [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)