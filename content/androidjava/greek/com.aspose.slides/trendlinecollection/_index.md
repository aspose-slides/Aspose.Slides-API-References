---
title: TrendlineCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή από Trendline
type: docs
url: /el/com.aspose.slides/trendlinecollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Αναπαριστά μια συλλογή από Trendline
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [add(int trendlineType)](#add-int-) | Προσθέτει τη νέα Trendline στο τέλος μιας συλλογής και την επιστρέφει. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Αφαιρεί την καθορισμένη τιμή. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [Trendline](../../com.aspose.slides/trendline).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Προσθέτει τη νέα Trendline στο τέλος μιας συλλογής και την επιστρέφει.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| trendlineType | int |  |

**Επιστρέφει:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διατρέξει τη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### getCount() {#getCount--}
```
public final int getCount()
```

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int