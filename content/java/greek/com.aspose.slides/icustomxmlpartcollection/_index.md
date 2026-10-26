---
title: ICustomXmlPartCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά τη συλλογή προσαρμοσμένων xml τμημάτων.
type: docs
url: /el/com.aspose.slides/icustomxmlpartcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Αναπαριστά τη συλλογή προσαρμοσμένων XML τμημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στο καθορισμένο ευρετήριο. |
| [add(byte[] xmlData)](#add-byte---) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [add(String xmlString)](#add-java.lang.String-) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το προσαρμοσμένο τμήμα xml στο καθορισμένο ευρετήριο. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Επιστρέφει το στοιχείο στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα ληφθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Το στοιχείο στο καθορισμένο ευρετήριο.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlData | byte[] | Τα xml δεδομένα του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργήθηκε προσαρμοσμένο τμήμα xml.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlString | java.lang.String | Το xml string του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργήθηκε προσαρμοσμένο τμήμα xml.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | java.io.InputStream | Το inputStream με τα xml δεδομένα του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργήθηκε προσαρμοσμένο τμήμα xml.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το προσαρμοσμένο τμήμα xml στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετρος:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Το προσαρμοσμένο τμήμα xml που θα αφαιρεθεί. |

**Επιστρέφει:**
boolean - αληθές εάν το στοιχείο αφαιρεθεί επιτυχώς· διαφορετικά, ψευδές.
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.