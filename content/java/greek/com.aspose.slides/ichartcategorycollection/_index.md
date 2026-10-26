---
title: IChartCategoryCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει τη συλλογή των
type: docs
url: /el/com.aspose.slides/ichartcategorycollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Represents collection of [IChartCategory](../../com.aspose.slides/ichartcategory)
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getUseCells()](#getUseCells--) | Εάν true, τότε το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Εάν true, τότε το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. |
| [add(Object value)](#add-java.lang.Object-) | Δημιουργεί νέο [IChartCategory](../../com.aspose.slides/ichartcategory) από την τιμή και το προσθέτει στη συλλογή. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Αναζητά το καθορισμένο [IChartCategory](../../com.aspose.slides/ichartcategory) και επιστρέφει το μηδενική-βάση δείκτη της πρώτης εμφάνισης εντός ολόκληρης της Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον δοσμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Το στοιχείο στον καθορισμένο δείκτη.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean.

**Returns:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Returns count of category grouping levels used. Is more then one for multilevel categories. Read-only int.

**Returns:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

If category exists in collection, return it. Else creates new chart category from [IChartDataCell](../../com.aspose.slides/ichartdatacell) and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κελί που χρησιμοποιείται για τη δημιουργία κατηγορίας γραφήματος. |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστέθηκε ή υπάρχουσα κατηγορία.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Creates new [IChartCategory](../../com.aspose.slides/ichartcategory) from value and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Η τιμή.

--------------------

This method adds worksheet with name AUTO_DATA and adds all values there. If you use [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστέθηκε [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Searches for the specified [IChartCategory](../../com.aspose.slides/ichartcategory) and returns the zero-based index of the first occurrence within the entire Collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Κατηγορία γραφήματος. |

**Returns:**
int - Το μηδενική-βάση δείκτη της πρώτης εμφάνισης της τιμής εντός ολόκληρης της CollectionBase, εάν βρεθεί· διαφορετικά, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Η τιμή. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the element at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης της κατηγορίας προς αφαίρεση. |

### clear() {#clear--}
```
public abstract void clear()
```

Removes all elements from the collection.