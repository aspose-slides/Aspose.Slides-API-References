---
title: CaptionsCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή των κλειστών λεζαντών.
type: docs
url: /el/com.aspose.slides/captionscollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Αναπαριστά μια συλλογή των κλειστών λεζαντών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τις κλειστές λεζάντες στο συγκεκριμένο δείκτη. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Προσθέτει κλειστές λεζάντες WebVTT στο τέλος της συλλογής. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Προσθέτει κλειστές λεζάντες WebVTT στο τέλος της συλλογής από ροή. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Αφαιρεί τις συγκεκριμένες κλειστές λεζάντες από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τις κλειστές λεζάντες στο συγκεκριμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις κλειστές λεζάντες από τη συλλογή. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Επιστρέφει τις κλειστές λεζάντες στο συγκεκριμένο δείκτη. Μόνο για ανάγνωση [ICaptions](../../com.aspose.slides/icaptions).

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

Προσθέτει κλειστές λεζάντες WebVTT στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | java.lang.String | Η ετικέτα των κλειστών λεζαντών. |
| filePath | java.lang.String | Η διαδρομή του αρχείου WebVTT. |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions) - Το προστιθέμενο [ICaptions](../../com.aspose.slides/icaptions) αντικείμενο.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Προσθέτει κλειστές λεζάντες WebVTT στο τέλος της συλλογής από μια ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | java.lang.String | Η ετικέτα των κλειστών λεζαντών. |
| stream | java.io.InputStream | Η εισερχόμενη ροή που περιέχει δεδομένα σε μορφή WebVTT. |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions) - Το προστιθέμενο [ICaptions](../../com.aspose.slides/icaptions) αντικείμενο.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Αφαιρεί τις συγκεκριμένες κλειστές λεζάντες από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Οι κλειστές λεζάντες προς αφαίρεση. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί τις κλειστές λεζάντες στο συγκεκριμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |
### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλες τις κλειστές λεζάντες από τη συλλογή.
### getCount() {#getCount--}
```
public final int getCount()
```

Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Ένας  System.Collections.Generic.IEnumerator1  που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.