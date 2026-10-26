---
title: IMathElementCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει μια συλλογή μαθηματικών στοιχείων MathElement.
type: docs
url: /el/com.aspose.slides/imathelementcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Αντιπροσωπεύει μια συλλογή μαθηματικών στοιχείων (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Προσθέτει ένα μαθηματικό στοιχείο στο τέλος της συλλογής. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Καθορίζει τη θέση ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Εισάγει ένα μαθηματικό στοιχείο στη συλλογή στη συγκεκριμένη θέση. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Αντιγραφή σε καθορισμένο πίνακα. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. Μόνο ανάγνωση [IMathElement](../../com.aspose.slides/imathelement).

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
| index | int | Ο μηδενικός δείκτης του αντικειμένου που θα ληφθεί |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο ανάγνωση int.

--------------------

> ```
> Example:
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
> Example:
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

Καθορίζει τη θέση ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή.

--------------------

> ```
> Example:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Η θέση του στοιχείου εάν βρεθεί στη συλλογή· διαφορετικά, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Εισάγει ένα μαθηματικό στοιχείο στη συλλογή στη συγκεκριμένη θέση.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση όπου θα εισαχθεί το IMathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το IMathElement που θα εισαχθεί. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

--------------------

> ```
> Example:
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
> Example:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το αντικείμενο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο βρεθεί στη συλλογή· διαφορετικά, false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

--------------------

> ```
> Example:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το αντικείμενο που θα αφαιρεθεί από τη συλλογή. |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο αφαιρεθεί επιτυχώς από τη συλλογή· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false εάν το αντικείμενο δεν βρεθεί στην αρχική συλλογή.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής.

--------------------

> ```
> Example:
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
| index | int | Ο μηδενικός δείκτης του στοιχείου προς αφαίρεση. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Αντιγραφή σε καθορισμένο πίνακα.

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
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Ο πίνακας στον οποίο θα γίνει η αντιγραφή. |
| arrayIndex | int | Δείκτης από όπου θα ξεκινήσει η αντιγραφή. |