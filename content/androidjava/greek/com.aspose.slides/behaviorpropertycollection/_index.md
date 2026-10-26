---
title: BehaviorPropertyCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τις ιδιότητες χρονισμού για τη συμπεριφορά του εφέ.
type: docs
url: /el/com.aspose.slides/behaviorpropertycollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Αναπαριστά τις ιδιότητες χρονισμού για τη συμπεριφορά του εφέ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των ιδιοτήτων που αποθηκεύονται στη συλλογή. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Προσθέτει μια νέα ιδιότητα στη συλλογή. |
| [add(String propertyValue)](#add-java.lang.String-) | Προσθέτει μια νέα ιδιότητα στη συλλογή. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στη List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου με βάση την τιμή ιδιότητας στη List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Εισάγει μια νέα ιδιότητα στη συλλογή στον καθορισμένο δείκτη. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Εισάγει μια νέα ιδιότητα (με την καθορισμένη τιμή ιδιότητας) στη συλλογή στον καθορισμένο δείκτη. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Array, αρχίζοντας από έναν συγκεκριμένο δείκτη Array. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ιδιότητα στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις ιδιότητες από τη συλλογή. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια ιδιότητα στον καθορισμένο δείκτη. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Ορίζει μια ιδιότητα στον καθορισμένο δείκτη. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναλήπτη που διατρέχει τη συλλογή. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των ιδιοτήτων που αποθηκεύονται στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά, false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


Προσθέτει μια νέα ιδιότητα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Ιδιότητα προς προσθήκη. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


Προσθέτει μια νέα ιδιότητα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας προς προσθήκη. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στη List.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Το αντικείμενο που πρέπει να εντοπιστεί στη List. |

**Επιστρέφει:**
int - Το δείκτη του στοιχείου εάν βρεθεί στη λίστα· διαφορετικά, -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου με βάση την τιμή ιδιότητας στη List.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | τιμή της ιδιότητας |

**Επιστρέφει:**
int - Το δείκτη της ιδιότητας με την καθορισμένη τιμή
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


Εισάγει μια νέα ιδιότητα στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης όπου πρέπει να εισαχθεί μια νέα ιδιότητα. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Ιδιότητα προς προσθήκη. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


Εισάγει μια νέα ιδιότητα (με την καθορισμένη τιμή ιδιότητας) στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης όπου πρέπει να εισαχθεί μια νέα ιδιότητα. |
| propertyValue | java.lang.String | Τιμή της ιδιότητας προς προσθήκη. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Array, αρχίζοντας από έναν συγκεκριμένο δείκτη Array.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Ο μονοδιάστατος Array που είναι ο προορισμός των αντιγραμμένων στοιχείων από [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Array πρέπει να έχει μηδενική βάση. |
| arrayIndex | int | Ο μηδενικός δείκτης στον array από τον οποίο ξεκινά η αντιγραφή. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Ιδιότητα προς αφαίρεση. |

**Επιστρέφει:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας προς αφαίρεση. |

**Επιστρέφει:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί την ιδιότητα στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της ιδιότητας που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλες τις ιδιότητες από τη συλλογή.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Η ιδιότητα που πρέπει να εντοπιστεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το item βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | Τιμή της ιδιότητας προς εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το propertyValue βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


Επιστρέφει μια ιδιότητα στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας ιδιότητας προς επιστροφή. |

**Επιστρέφει:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animation behavior property.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


Ορίζει μια ιδιότητα στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας ιδιότητας προς επιστροφή. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


Επιστρέφει έναν επαναλήπτη που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη της συλλογής.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Επιστρέφει:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Επιστρέφει:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Επιστρέφει:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.