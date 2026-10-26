---
title: CustomXmlPartCollection
second_title: Αναφορά API Java για το Aspose.Slides για Android
description: Αντιπροσωπεύει μια συλλογή προσαρμοσμένων τμημάτων xml.
type: docs
url: /el/com.aspose.slides/customxmlpartcollection/
---
**Κληρονομικότητα:**  
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Αντιπροσωπεύει μια συλλογή προσαρμοσμένων τμημάτων xml.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στο καθορισμένο δείκτη. |
| [size()](#size--) | Επιστρέφει τον αριθμό των προσαρμοσμένων τμημάτων xml στη συλλογή. |
| [add(String xmlString)](#add-java.lang.String-) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [add(byte[] xmlData)](#add-byte---) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το προσαρμοσμένο τμήμα xml στο καθορισμένο δείκτη. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει σε καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής ως προς τα νήματα). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν ατγομετρητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Επιστρέφει το στοιχείο στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα ληφθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Το στοιχείο στο καθορισμένο δείκτη.

### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των προσαρμοσμένων τμημάτων xml στη συλλογή. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlString | java.lang.String | Η συμβολοσειρά xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο τμήμα xml.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlData | byte[] | Τα δεδομένα xml του νέου τμήματος που θα προστεθούν. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο τμήμα xml.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | java.io.InputStream | Το inputStream με δεδομένα xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο τμήμα xml.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το προσαρμοσμένο τμήμα xml στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα αφαιρεθεί. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Το προσαρμοσμένο τμήμα xml που θα αφαιρεθεί. |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο αφαιρέθηκε επιτυχώς· διαφορετικά, false.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας στον οποίο θα γίνει η αντιγραφή. |
| index | int | Δείκτης από τον οποίο ξεκινά η αντιγραφή. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής ως προς τα νήματα). Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο-ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Επιστρέφει έναν ατγομετρητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject