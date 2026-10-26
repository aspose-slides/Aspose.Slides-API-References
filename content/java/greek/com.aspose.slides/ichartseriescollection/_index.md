---
title: IChartSeriesCollection
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει τη συλλογή του
type: docs
url: /el/com.aspose.slides/ichartseriescollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Αντιπροσωπεύει τη συλλογή του [IChartSeries](../../com.aspose.slides/ichartseries)
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [add(int type)](#add-int-) | Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή. |
| [insert(int index, int type)](#insert-int-int-) | Δημιουργεί νέα σειρά γραφήματος και την εισάγει στη συλλογή. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Δημιουργεί νέα σειρά γραφήματος από το [IChartDataCell](../../com.aspose.slides/ichartdatacell) και την προσθέτει στη συλλογή. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Δημιουργεί νέα σειρά γραφήματος από το [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) και την προσθέτει στη συλλογή. |
| [add(String name, int type)](#add-java.lang.String-int-) | Δημιουργεί νέα σειρά γραφήματος από την τιμή και την προσθέτει στη συλλογή. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Αναζητά το καθορισμένο [IChartSeries](../../com.aspose.slides/ichartseries) και επιστρέφει το μηδενικό ευρετήριο της πρώτης εμφάνισης στο σύνολο της Συλλογής. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο καθορισμένο δείκτη |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία (συμπεριλαμβανομένου του στυλ γραφήματος) από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Λαμβάνει το στοιχείο στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Το στοιχείο στο καθορισμένο δείκτη.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Τύπος σειράς |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Νέα σειρά γραφήματος.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Δημιουργεί νέα σειρά γραφήματος και την εισάγει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης για εισαγωγή |
| type | int | Τύπος γραφήματος [ChartType](../../com.aspose.slides/charttype) |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Νέα σειρά γραφήματος [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Δημιουργεί νέα σειρά γραφήματος από το [IChartDataCell](../../com.aspose.slides/ichartdatacell) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κελί που περιέχει το όνομα της σειράς. |
| type | int | Ορισμός τύπου σειράς

--------------------

Εάν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το ευρετήριό της. |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστιθέμενη σειρά γραφήματος ή σειρά που υπάρχει ήδη στη συλλογή.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Δημιουργεί νέα σειρά γραφήματος από το [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Κελιά που περιέχουν το όνομα της σειράς. |
| type | int | Ορισμός τύπου σειράς

--------------------

Εάν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το ευρετήριό της. |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστιθέμενη σειρά γραφήματος ή σειρά που υπάρχει ήδη στη συλλογή.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Δημιουργεί νέα σειρά γραφήματος από την τιμή και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα σειράς. |
| type | int | Τύπος σειράς |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Η προστιθέμενη σειρά γραφήματος.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Αναζητά το καθορισμένο [IChartSeries](../../com.aspose.slides/ichartseries) και επιστρέφει το μηδενικό ευρετήριο της πρώτης εμφάνισης στο σύνολο της Συλλογής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Τιμή σειράς γραφήματος. |

**Επιστρέφει:**
int - Το μηδενικό ευρετήριο της πρώτης εμφάνισης της τιμής στο σύνολο CollectionBase, εάν βρεθεί· αλλιώς, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Η τιμή. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στο καθορισμένο δείκτη

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία (συμπεριλαμβανομένου του στυλ γραφήματος) από τη συλλογή.