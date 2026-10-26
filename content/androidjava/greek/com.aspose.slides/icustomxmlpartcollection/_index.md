---
title: ICustomXmlPartCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τη συλλογή προσαρμοσμένων τμημάτων xml.
type: docs
url: /el/com.aspose.slides/icustomxmlpartcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Αναπαριστά τη συλλογή προσαρμοσμένων τμημάτων xml.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [add(byte[] xmlData)](#add-byte---) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [add(String xmlString)](#add-java.lang.String-) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Προσθέτει νέο προσαρμοσμένο τμήμα xml. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το προσαρμοσμένο τμήμα xml στον καθορισμένο δείκτη. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Επιστρέφει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα ληφθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Το στοιχείο στον καθορισμένο δείκτη.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlData | byte[] | Τα δεδομένα xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο τμήμα xml.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlString | java.lang.String | Η συμβολοσειρά xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο τμήμα xml.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Προσθέτει νέο προσαρμοσμένο τμήμα xml.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | java.io.InputStream | Το inputStream με τα δεδομένα xml του νέου τμήματος που θα προστεθεί. |

**Επιστρέφει:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Δημιουργημένο προσαρμοσμένο τμήμα xml.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το προσαρμοσμένο τμήμα xml στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα αφαιρεθεί. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Το προσαρμοσμένο τμήμα xml που θα αφαιρεθεί. |

**Επιστρέφει:**
boolean - true εάν το στοιχείο αφαιρεθεί επιτυχώς· διαφορετικά, false.
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.