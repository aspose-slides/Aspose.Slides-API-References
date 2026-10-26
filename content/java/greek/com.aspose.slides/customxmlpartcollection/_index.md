---
title: CustomXmlPartCollection
second_title: Aspose.Slides για την Java API Αναφορά
description: Αναπαριστά συλλογή προσαρμοσμένων xml τμημάτων.
type: docs
url: /el/com.aspose.slides/customxmlpartcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Αντιπροσωπεύει τη συλλογή προσαρμοσμένων xml τμημάτων.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [size()](#size--) | Επιστρέφει τον αριθμό των προσαρμοσμένων xml τμημάτων στη συλλογή. |
| [add(String xmlString)](#add-java.lang.String-) | Προσθέτει νέο προσαρμοσμένο xml τμήμα. |
| [add(byte[] xmlData)](#add-byte---) | Προσθέτει νέο προσαρμοσμένο xml τμήμα. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Προσθέτει νέο προσαρμοσμένο xml τμήμα. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το προσαρμοσμένο xml τμήμα στον καθορισμένο δείκτη. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει σε καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Επιστρέφει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα ληφθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Το στοιχείο στον καθορισμένο δείκτη.

### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των προσαρμοσμένων xml τμημάτων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Προσθέτει νέο προσαρμοσμένο xml τμήμα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | Η συμβολοσειρά xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο xml τμήμα.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Προσθέτει νέο προσαρμοσμένο xml τμήμα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | Τα δεδομένα xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο xml τμήμα.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Προσθέτει νέο προσαρμοσμένο xml τμήμα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Το inputStream με τα δεδομένα xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο xml τμήμα.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το προσαρμοσμένο xml τμήμα στον καθορισμένο δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα αφαιρεθεί. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Το προσαρμοσμένο xml τμήμα που θα αφαιρεθεί. |

**Επιστρέφει:**
boolean - true αν το αντικείμενο αφαιρέθηκε επιτυχώς· διαφορετικά, false.

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει σε καθορισμένο πίνακα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού. |
| index | int | Δείκτης εκκίνησης αντιγραφής. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject