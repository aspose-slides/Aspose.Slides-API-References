---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides για το Java API Αναφορά
description: Αναπαριστά τις ιδιότητες χρονομέτρησης για τη συμπεριφορά του εφέ.
type: docs
url: /el/com.aspose.slides/ibehaviorpropertycollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Αναπαριστά τις ιδιότητες χρονομέτρησης για τη συμπεριφορά του εφέ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Προσθέτει μια νέα ιδιότητα στη συλλογή. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου με βάση την τιμή της ιδιότητας στη Λίστα. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Εισάγει μια νέα ιδιότητα (με την καθορισμένη τιμή ιδιότητας) στη συλλογή στον καθορισμένο δείκτη. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


Προσθέτει μια νέα ιδιότητα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας προς προσθήκη. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου με βάση την τιμή της ιδιότητας στη Λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | τιμή της ιδιότητας |

**Επιστρέφει:**
int - Ο δείκτης της ιδιότητας με την καθορισμένη τιμή
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


Εισάγει μια νέα ιδιότητα (με την καθορισμένη τιμή ιδιότητας) στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης όπου πρέπει να εισαχθεί η νέα ιδιότητα. |
| propertyValue | java.lang.String | Τιμή της ιδιότητας προς προσθήκη. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας προς αφαίρεση. |

**Επιστρέφει:**
boolean - Αληθές εάν μια ιδιότητα αφαιρέθηκε επιτυχώς
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας για εντόπιση στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - αληθές εάν η propertyValue βρέθηκε στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, ψευδής.