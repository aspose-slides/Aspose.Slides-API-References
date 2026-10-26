---
title: ITrendlineCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια συλλογή των TrendlineEx
type: docs
url: /el/com.aspose.slides/itrendlinecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Represents a collection of TrendlineEx
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [add(int trendlineType)](#add-int-) | Προσθέτει τη νέα Trendline στο τέλος μιας συλλογής και την επιστρέφει. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Αφαιρεί την καθορισμένη τιμή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [ITrendline](../../com.aspose.slides/itrendline).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Προσθέτει τη νέα Trendline στο τέλος μιας συλλογής και την επιστρέφει.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| trendlineType | int | Τύπος Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Επιστρέφει:**
[ITrendline](../../com.aspose.slides/itrendline) - Νέα Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline για αφαίρεση [ITrendline](../../com.aspose.slides/itrendline) |