---
title: IMathBlockCollection
second_title: Aspose.Slides για Java API Αναφορά
description: Συλλογή μαθηματικών μπλοκ IMathBlock
type: docs
url: /el/com.aspose.slides/imathblockcollection/
---
**All Implemented Interfaces:**
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

## Methods

| Method | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Προσθέτει το IMathBlock στο τέλος της συλλογής. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Εισάγει το IMathBlock στη συλλογή στον καθορισμένο δείκτη. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Καταργεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Καταργεί ένα στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Καθορίζει το δείκτη ενός συγκεκριμένου IMathBlock στη συλλογή. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Καταργεί όλα τα στοιχεία από τη συλλογή. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Προσθέτει το IMathBlock στο τέλος της συλλογής.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Ένα μαθηματικό μπλοκ που θα προστεθεί στο τέλος της συλλογής |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Εισάγει το IMathBlock στη συλλογή στον καθορισμένο δείκτη.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενισμός-βάση δείκτης στον οποίο θα εισαχθεί το στοιχείο. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το IMathBlock που θα εισαχθεί. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Καταργεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το αντικείμενο που θα καταργηθεί από τη συλλογή. |

**Returns:**
boolean - true αν το στοιχείο αφαιρέθηκε με επιτυχία από τη συλλογή· διαφορετικά, false. Η μέθοδος επιστρέφει επίσης false αν το στοιχείο δεν βρεθεί στην αρχική συλλογή.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Καταργεί ένα στοιχείο στον καθορισμένο δείκτη της συλλογής.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενισμός-βάση δείκτης του στοιχείου που θα αφαιρεθεί. |

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το αντικείμενο που θα εντοπιστεί στη συλλογή. |

**Returns:**
boolean - true αν το στοιχείο βρεθεί στη συλλογή· διαφορετικά, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Καθορίζει το δείκτη ενός συγκεκριμένου IMathBlock στη συλλογή.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Το στοιχείο που θα εντοπιστεί στη συλλογή. |

**Returns:**
int - Το δείκτη του στοιχείου αν βρεθεί στη συλλογή· διαφορετικά, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενισμός-βάση δείκτης του στοιχείου που θα ληφθεί. |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - Το μπλοκ ενός μαθηματικού κειμένου.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενισμός-βάση δείκτης του στοιχείου που θα τεθεί. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Το μπλοκ ενός μαθηματικού κειμένου. |

### clear() {#clear--}
```
public abstract void clear()
```

Καταργεί όλα τα στοιχεία από τη συλλογή.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```