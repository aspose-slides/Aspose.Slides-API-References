---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τις ιδιότητες χρονισμού για τη συμπεριφορά του εφέ.
type: docs
url: /el/com.aspose.slides/ibehaviorpropertycollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Αντιπροσωπεύει τις ιδιότητες χρονισμού για τη συμπεριφορά του εφέ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Προσθέτει μια νέα ιδιότητα στη συλλογή. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Καθορίζει το ευρετήριο ενός συγκεκριμένου στοιχείου με βάση την τιμή της ιδιότητας στη λίστα. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Εισάγει μια νέα ιδιότητα (με την καθορισμένη τιμή ιδιότητας) στη συλλογή στο καθορισμένο ευρετήριο. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Καθορίζει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Προσθέτει μια νέα ιδιότητα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας που θα προστεθεί. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Καθορίζει το ευρετήριο ενός συγκεκριμένου στοιχείου με βάση την τιμή της ιδιότητας στη λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | τιμή της ιδιότητας |

**Επιστρέφει:**
int - Το ευρετήριο της ιδιότητας με την καθορισμένη τιμή
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Εισάγει μια νέα ιδιότητα (με την καθορισμένη τιμή ιδιότητας) στη συλλογή στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο όπου πρέπει να εισαχθεί μια νέα ιδιότητα. |
| propertyValue | java.lang.String | Τιμή της ιδιότητας που θα προστεθεί. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας που θα αφαιρεθεί. |

**Επιστρέφει:**
boolean - Αληθές εάν μια ιδιότητα αφαιρεθεί επιτυχώς boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Καθορίζει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας για εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - αληθές εάν η propertyValue βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, ψευδές.