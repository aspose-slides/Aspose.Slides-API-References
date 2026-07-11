---
title: MathBlock
second_title: Αναφορά API του Aspose.Slides για Android μέσω Java
description: Καθορίζει μια παρουσία μαθηματικού κειμένου που περιλαμβάνεται σε ένα MathParagraph και ξεκινά σε ξεχωριστή γραμμή.
type: docs
url: /el/com.aspose.slides/mathblock/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Καθορίζει μια παρουσία μαθηματικού κειμένου που περιέχεται σε ένα MathParagraph και ξεκινά σε ξεχωριστή γραμμή. Όλες οι ζώνες μαθηματικών, συμπεριλαμβανομένων εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από math block.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBlock()](#MathBlock--) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί το καθορισμένο στοιχείο σε αυτό |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί τα καθορισμένα στοιχεία σε αυτό |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των θυγατρικών στοιχείων μαθηματικών που πραγματικά περιέχονται στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει ή ορίζει το IMathElement στο καθορισμένο δείκτη. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Λαμβάνει ή ορίζει το IMathElement στο καθορισμένο δείκτη. |
| [isReadOnly()](#isReadOnly--) | Επιστρέφει false επειδή η συλλογή των θυγατρικών στοιχείων μπορεί να τροποποιηθεί. |
| [getChildren()](#getChildren--) | Λαμβάνει τα θυγατρικά στοιχεία |
| [getParent_Immediate()](#getParent-Immediate--) | Επιστρέφει το αντικείμενο Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Προσθέτει ένα στοιχείο μαθηματικών στο τέλος της συλλογής. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Αντιγράφει σε καθορισμένο πίνακα. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν ενομετρητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου μαθηματικών στη συλλογή. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Εισάγει ένα MathElement στη συλλογή στο καθορισμένο δείκτη. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο καθορισμένο δείκτη της συλλογής. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό block |
| [join(String mathText)](#join-java.lang.String-) | Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό block |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Συνδέει ένα άλλο μαθηματικό block με αυτό |
| [delimit(char separatorCharacter)](#delimit-char-) | Οριοθετεί τα θυγατρικά στοιχεία με χαρακτήρα διαχωρισμού (χωρίς τις αγκύλες) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Περιβάλλει τα θυγατρικά στοιχεία αυτού του block σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Περιβάλλει τα θυγατρικά στοιχεία αυτού του block σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωρισμού |
| [toMathArray()](#toMathArray--) | Τοποθετεί τα θυγατρικά στοιχεία σε κάθετη διάταξη |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο αυτού του [MathBlock](../../com.aspose.slides/mathblock) ως MathML |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Αρχικοποιεί μια νέα παρουσία της κλάσης MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```


### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί το καθορισμένο στοιχείο σε αυτό

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Το μαθηματικό στοιχείο που θα τοποθετηθεί στο block |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί τα καθορισμένα στοιχεία σε αυτό

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Τα μαθηματικά στοιχεία που θα τοποθετηθούν στο block |

### getCount() {#getCount--}
```
public final int getCount()
```

Επιστρέφει τον αριθμό των θυγατρικών στοιχείων μαθηματικών που πραγματικά περιέχονται στη συλλογή. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Λαμβάνει ή ορίζει το IMathElement στο καθορισμένο δείκτη.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενισμένος δείκτης του στοιχείου |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement) - Το μαθηματικό στοιχείο.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Λαμβάνει ή ορίζει το IMathElement στο καθορισμένο δείκτη.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενισμένος δείκτης του στοιχείου |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Το μαθηματικό στοιχείο. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Επιστρέφει false επειδή η συλλογή των θυγατρικών στοιχείων μπορεί να τροποποιηθεί.

**Επιστρέφει:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει τα θυγατρικά στοιχεία

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Προσθέτει ένα στοιχείο μαθηματικών στο τέλος της συλλογής.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το IMathElement που θα προστεθεί στο τέλος της συλλογής. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το αντικείμενο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο βρεθεί στη συλλογή· διαφορετικά, false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Αντιγράφει σε καθορισμένο πίνακα.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IMathElement[]](../../com.aspose.slides/imathelement) | Πίνακας προς αντιγραφή. |
| arrayIndex | int | Δείκτης έναρξης αντιγραφής. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το αντικείμενο που θα αφαιρεθεί από τη συλλογή. |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο αφαιρεθεί επιτυχώς από τη συλλογή· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false εάν το αντικείμενο δεν βρεθεί στην αρχική συλλογή.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Επιστρέφει έναν ενομετρητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.IEnumerator - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου μαθηματικών στη συλλογή.

--------------------

> ```
> Παράδειγμα:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Ο δείκτης του αντικειμένου εάν βρεθεί στη συλλογή· διαφορετικά, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Εισάγει ένα MathElement στη συλλογή στο καθορισμένο δείκτη.

--------------------

> ```
> Παράδειγμα:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενισμένος δείκτης στον οποίο πρέπει να εισαχθεί το MathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το MathElement που θα εισαχθεί. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στο καθορισμένο δείκτη της συλλογής.

--------------------

> ```
> Παράδειγμα:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενισμένος δείκτης του στοιχείου που θα αφαιρεθεί. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό block

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο που θα ενωθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Η τρέχουσα παρουσία του IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό block

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | java.lang.String | Μαθηματικό κείμενο που θα ενωθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ένα νέο IMathBlock που περιέχει αυτήν την παρουσία και το καθορισμένο όρισμα
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Συνδέει ένα άλλο μαθηματικό block με αυτό

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Το μπλοκ που θα συνδεθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - αυτό το μαθηματικό block μετά τη σύνδεση
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Οριοθετεί τα θυγατρικά στοιχεία με χαρακτήρα διαχωρισμού (χωρίς τις αγκύλες)

--------------------

> ```
> Παράδειγμα:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char | Χαρακτήρας διαχωρισμού |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το στοιχείο μαθηματικών τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Περιβάλλει τα θυγατρικά στοιχεία αυτού του block σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το στοιχείο μαθηματικών τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Περιβάλλει τα θυγατρικά στοιχεία αυτού του block σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωρισμού

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |
| separatorCharacter | char | Χαρακτήρας διαχωρισμού |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το στοιχείο μαθηματικών τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο και διαχωριστικό
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Τοποθετεί τα θυγατρικά στοιχεία σε κάθετη διάταξη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Επιστρέφει:**
[IMathArray](../../com.aspose.slides/imatharray) - Νέα παρουσία τύπου [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο αυτού του [MathBlock](../../com.aspose.slides/mathblock) ως MathML

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Στόχος ροής |