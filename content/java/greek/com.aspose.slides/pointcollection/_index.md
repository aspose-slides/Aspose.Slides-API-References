---
title: PointCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά συλλογή σημείων κίνησης.
type: docs
url: /el/com.aspose.slides/pointcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Αντιπροσωπεύει τη συλλογή σημείων κίνησης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Returns the number of points in the collection. |
| [get_Item(int index)](#get-Item-int-) | Returns a point at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Επιστρέφει τον αριθμό των σημείων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Επιστρέφει ένα σημείο στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[IPoint](../../com.aspose.slides/ipoint) - The [IPoint](../../com.aspose.slides/ipoint) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - An java.util.Iterator for the entire collection.