---
title: ITagCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά τη συλλογή των ετικετών, ζεύγη συμβολοσειρών που ορίζονται από το χρήστη
type: docs
url: /el/com.aspose.slides/itagcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Αντιπροσωπεύει τη συλλογή των ετικετών (ζεύγη συμβολοσειρών που ορίζονται από το χρήστη)
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Προσθέτει μια νέα ετικέτα στη συλλογή. |
| [remove(String name)](#remove-java.lang.String-) | Αφαιρεί την ετικέτα με το συγκεκριμένο όνομα από τη συλλογή. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Επιστρέφει τον μηδενικής βάσης δείκτη του συγκεκριμένου κλειδιού στη συλλογή. |
| [contains(String name)](#contains-java.lang.String-) | Καθορίζει αν η συλλογή περιέχει ένα συγκεκριμένο όνομα. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ετικέτα στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις ετικέτες από τη συλλογή. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Επιστρέφει την τιμή μιας ετικέτας στον καθορισμένο δείκτη. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Επιστρέφει το κλειδί μιας ετικέτας στον καθορισμένο δείκτη. |
| [getNamesOfTags()](#getNamesOfTags--) | Επιστρέφει τα ονόματα των ετικετών. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Επιστρέφει ή ορίζει ένα ζεύγος κλειδί-τιμή μιας ετικέτας. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Επιστρέφει ή ορίζει ένα ζεύγος κλειδί-τιμή μιας ετικέτας. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Προσθέτει μια νέα ετικέτα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ετικέτας. |
| value | java.lang.String | Η τιμή της ετικέτας. |

**Επιστρέφει:**
int - Ο δείκτης της προστεθειμένης ετικέτας.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Αφαιρεί την ετικέτα με ένα συγκεκριμένο όνομα από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ετικέτας προς αφαίρεση. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Επιστρέφει τον μηδενικής βάσης δείκτη του συγκεκριμένου κλειδιού στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Ο μηδενικής βάσης δείκτης του κλειδιού, εάν βρεθεί στη συλλογή· διαφορετικά, -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Καθορίζει αν η συλλογή περιέχει ένα συγκεκριμένο όνομα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το κλειδί που θα εντοπιστεί. |

**Επιστρέφει:**
boolean - True εάν η συλλογή περιέχει μια ετικέτα με το συγκεκριμένο κλειδί· διαφορετικά, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί την ετικέτα στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης της ετικέτας προς αφαίρεση. |
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις ετικέτες από τη συλλογή.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Επιστρέφει την τιμή μιας ετικέτας στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της ετικέτας προς επιστροφή. |

**Επιστρέφει:**
java.lang.String - Τιμή μιας ετικέτας.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Επιστρέφει το κλειδί μιας ετικέτας στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της ετικέτας προς επιστροφή. |

**Επιστρέφει:**
java.lang.String - Κλειδί μιας ετικέτας.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Επιστρέφει τα ονόματα των ετικετών.

**Επιστρέφει:**
java.lang.String[] - Ονόματα των ετικετών.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Επιστρέφει ή ορίζει ένα ζεύγος κλειδί-τιμή μιας ετικέτας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Κλειδί μιας ετικέτας. |

**Επιστρέφει:**
java.lang.String - Τιμή μιας ετικέτας.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Επιστρέφει ή ορίζει ένα ζεύγος κλειδί-τιμή μιας ετικέτας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Κλειδί μιας ετικέτας. |
| value | java.lang.String |  |