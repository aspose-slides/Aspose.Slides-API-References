---
title: IMathBlockCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Συλλογή μαθηματικών μπλοκ IMathBlock
type: docs
url: /el/com.aspose.slides/imathblockcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Συλλογή μαθηματικών μπλοκ (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Προσθέτει IMathBlock στο τέλος της συλλογής. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Εισάγει IMathBlock στη συλλογή στον καθορισμένο δείκτη. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Καθορίζει τον δείκτη ενός συγκεκριμένου IMMathBlock στη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```


Προσθέτει IMMathBlock στο τέλος της συλλογής.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Ένα μαθηματικό μπλοκ που θα προστεθεί στο τέλος της συλλογής |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


Εισάγει IMMathBlock στη συλλογή στον καθορισμένο δείκτη.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το στοιχείο. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το IMMathBlock που θα εισαχθεί. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το αντικείμενο που θα αφαιρεθεί από τη συλλογή. |

**Επιστρέφει:**
boolean - true εάν το στοιχείο αφαιρεθεί επιτυχώς από τη συλλογή· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false εάν το στοιχείο δεν βρεθεί στην αρχική συλλογή.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί ένα στοιχείο στον καθορισμένο δείκτη της συλλογής.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```


Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το αντικείμενο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
boolean - true εάν το στοιχείο βρεθεί στη συλλογή· διαφορετικά, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```


Καθορίζει τον δείκτη ενός συγκεκριμένου IMMathBlock στη συλλογή.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το στοιχείο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Ο δείκτης του στοιχείου εάν βρεθεί στη συλλογή· διαφορετικά, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα ληφθεί. |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Το μπλοκ ενός μαθηματικού κειμένου.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα οριστεί. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Το μπλοκ ενός μαθηματικού κειμένου. |

### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```