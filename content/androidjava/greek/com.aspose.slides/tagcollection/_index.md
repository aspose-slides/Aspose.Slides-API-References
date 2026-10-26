---
title: TagCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει τη συλλογή ετικετών, ζευγών συμβολοσειρών που καθορίζονται από τον χρήστη
type: docs
url: /el/com.aspose.slides/tagcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Represents the collection of tags (user defined pairs of strings)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των ετικετών στη συλλογή. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Προσθέτει μια νέα ετικέτα στη συλλογή. |
| [remove(String name)](#remove-java.lang.String-) | Αφαιρεί την ετικέτα με το συγκεκριμένο όνομα από τη συλλογή. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Επιστρέφει το μηδενικό (zero-based) ευρετήριο του καθορισμένου κλειδιού στη συλλογή. |
| [contains(String name)](#contains-java.lang.String-) | Καθορίζει εάν η συλλογή περιέχει ένα συγκεκριμένο όνομα. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ετικέτα στο καθορισμένο ευρετήριο. |
| [clear()](#clear--) | Αφαιρεί όλες τις ετικέτες από τη συλλογή. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Επιστρέφει την τιμή μιας ετικέτας στο καθορισμένο ευρετήριο. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Επιστρέφει το κλειδί μιας ετικέτας στο καθορισμένο ευρετήριο. |
| [getNamesOfTags()](#getNamesOfTags--) | Επιστρέφει τα ονόματα των ετικετών. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Επιστρέφει ή ορίζει ένα ζεύγος κλειδιού-τιμής μιας ετικέτας. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Επιστρέφει ή ορίζει ένα ζεύγος κλειδιού-τιμής μιας ετικέτας. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των ετικετών στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Προσθέτει μια νέα ετικέτα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ετικέτας. |
| value | java.lang.String | Η τιμή της ετικέτας. |

**Επιστρέφει:**
int - Το ευρετήριο της προστιθέμενης ετικέτας.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Αφαιρεί την ετικέτα με το συγκεκριμένο όνομα από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ετικέτας προς αφαίρεση. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Επιστρέφει το μηδενικό (zero-based) ευρετήριο του καθορισμένου κλειδιού στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Το μηδενικό ευρετήριο του κλειδιού, εάν το κλειδί βρεθεί στη συλλογή· διαφορετικά, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Καθορίζει εάν η συλλογή περιέχει ένα συγκεκριμένο όνομα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το κλειδί που θα εντοπιστεί. |

**Επιστρέφει:**
boolean - True εάν η συλλογή περιέχει μια ετικέτα με το καθορισμένο κλειδί· διαφορετικά, false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί την ετικέτα στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό ευρετήριο της ετικέτας προς αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλες τις ετικέτες από τη συλλογή.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Επιστρέφει την τιμή μιας ετικέτας στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο της ετικέτας για επιστροφή. |

**Επιστρέφει:**
java.lang.String - Τιμή μιας ετικέτας.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Επιστρέφει το κλειδί μιας ετικέτας στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο της ετικέτας για επιστροφή. |

**Επιστρέφει:**
java.lang.String - Κλειδί μιας ετικέτας.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Επιστρέφει τα ονόματα των ετικετών.

**Επιστρέφει:**
java.lang.String[] - Ονόματα των ετικετών.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Επιστρέφει ή ορίζει ένα ζεύγος κλειδιού-τιμής μιας ετικέτας.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Κλειδί μιας ετικέτας. |

**Επιστρέφει:**
java.lang.String - Τιμή μιας ετικέτας.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Επιστρέφει ή ορίζει ένα ζεύγος κλειδιού-τιμής μιας ετικέτας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Κλειδί μιας ετικέτας. |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προς συμπλήρωση. |
| index | int | Αρχική θέση στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

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
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Επιστρέφει έναν enumerator που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Έναν IGenericEnumerator που μπορεί να χρησιμοποιηθεί για διασχίζει τη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Έναν java.util.Iterator για ολόκληρη τη συλλογή.