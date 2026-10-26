---
title: ICaptionsCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια συλλογή των κλειστών υποτίτλων.
type: docs
url: /el/com.aspose.slides/icaptionscollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Αναπαριστά μια συλλογή των κλειστών υποτίτλων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τους κλειστούς υπότιτλους στο καθορισμένο δείκτη. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής από ροή. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Αφαιρεί τους καθορισμένους κλειστούς υπότιτλους από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τους κλειστούς υπότιτλους στο καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλους τους κλειστούς υπότιτλους από τη συλλογή. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

Επιστρέφει τους κλειστούς υπότιτλους στο καθορισμένο δείκτη. Μόνο για ανάγνωση [ICaptions](../../com.aspose.slides/icaptions).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | java.lang.String | Η ετικέτα των κλειστών υποτίτλων. |
| filePath | java.lang.String | Η διαδρομή του αρχείου WebVTT. |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions) - Το προστιθέμενο [ICaptions](../../com.aspose.slides/icaptions) αντικείμενο.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | java.lang.String | Η ετικέτα των κλειστών υποτίτλων. |
| stream | java.io.InputStream | Η ροή εισόδου που περιέχει δεδομένα σε μορφή WebVTT. |

**Επιστρέφει:**
[ICaptions](../../com.aspose.slides/icaptions) - Το προστιθέμενο [ICaptions](../../com.aspose.slides/icaptions) αντικείμενο.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Αφαιρεί τους καθορισμένους κλειστούς υπότιτλους από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Οι κλειστοί υπότιτλοι προς αφαίρεση. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί τους κλειστούς υπότιτλους στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης των κλειστών υποτίτλων προς αφαίρεση. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλους τους κλειστούς υπότιτλους από τη συλλογή.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο για ανάγνωση int .

**Επιστρέφει:**
int