---
title: CaptionsCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή των κλειστών υποτίτλων.
type: docs
url: /el/com.aspose.slides/captionscollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Αντιπροσωπεύει μια συλλογή των κλειστών υποτίτλων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τους κλειστούς υπότιτλους στον καθορισμένο δείκτη. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής από ροή. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Αφαιρεί τους καθορισμένους κλειστούς υπότιτλους από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τους κλειστούς υπότιτλους στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλους τους κλειστούς υπότιτλους από τη συλλογή. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Επιστρέφει τους κλειστούς υπότιτλους στον καθορισμένο δείκτη. Μόνο-ανάγνωση [ICaptions](../../com.aspose.slides/icaptions).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | java.lang.String | Η ετικέτα των κλειστών υποτίτλων. |
| filePath | java.lang.String | Η διαδρομή προς το αρχείο WebVTT. |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions) - Η προστιθέμενη [ICaptions](../../com.aspose.slides/icaptions) αντίγραφο.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής από μια ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | java.lang.String | Η ετικέτα των κλειστών υποτίτλων. |
| stream | java.io.InputStream | Η ροή εισόδου που περιέχει δεδομένα σε μορφή WebVTT. |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions) - Η προστιθέμενη [ICaptions](../../com.aspose.slides/icaptions) αντίγραφο.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Αφαιρεί τους καθορισμένους κλειστούς υπότιτλους από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Οι κλειστοί υπότιτλοι που θα αφαιρεθούν. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί τους κλειστούς υπότιτλους στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης των κλειστών υποτίτλων που θα αφαιρεθούν. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλους τους κλειστούς υπότιτλους από τη συλλογή.

### getCount() {#getCount--}
```
public final int getCount()
```

Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο-ανάγνωση  int .

**Επιστρέφει:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Ένας  System.Collections.Generic.IEnumerator1  που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.