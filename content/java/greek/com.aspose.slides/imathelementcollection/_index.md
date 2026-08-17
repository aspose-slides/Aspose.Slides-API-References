---
title: IMathElementCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια συλλογή μαθηματικών στοιχείων MathElement.
type: docs
url: /el/com.aspose.slides/imathelementcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Αναπαριστά μια συλλογή μαθηματικών στοιχείων (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Προσθέτει ένα μαθηματικό στοιχείο στο τέλος της συλλογής. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Καθορίζει τον δείκτη ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Εισάγει ένα μαθηματικό στοιχείο στη συλλογή στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Αντιγραφή σε συγκεκριμένο πίνακα. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του αντικειμένου προς λήψη. |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```


**Επιστρέφει:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


Προσθέτει ένα μαθηματικό στοιχείο στο τέλος της συλλογής.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το IMathElement που θα προστεθεί στο τέλος της συλλογής. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


Καθορίζει τον δείκτη ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο προς εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int - Ο δείκτης του στοιχείου αν βρεθεί στη συλλογή· διαφορετικά, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


Εισάγει ένα μαθηματικό στοιχείο στη συλλογή στον καθορισμένο δείκτη.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το IMathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το IMathElement προς εισαγωγή. |

### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```


### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```


Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το αντικείμενο προς εντοπισμό στη συλλογή. |

**Επιστρέφει:**
boolean - true αν το αντικείμενο βρεθεί στη συλλογή· διαφορετικά, false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το αντικείμενο προς αφαίρεση από τη συλλογή. |

**Επιστρέφει:**
boolean - true αν το αντικείμενο αφαιρεθεί με επιτυχία από τη συλλογή· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false αν το αντικείμενο δεν βρεθεί στην αρχική συλλογή.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρέει το στοιχείο στον καθορισμένο δείκτη της συλλογής.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου προς αφαίρεση. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


Αντιγραφή σε συγκεκριμένο πίνακα.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Πίνακας προς αντιγραφή. |
| arrayIndex | int | Δείκτης έναρξης αντιγραφής. |