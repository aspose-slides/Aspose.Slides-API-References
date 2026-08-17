---
title: MathBlock
second_title: Aspose.Slides για Java Αναφορά API
description: Καθορίζει μια παρουσία μαθηματικού κειμένου που περιέχεται σε ένα MathParagraph και αρχίζει σε δική του γραμμή.
type: docs
url: /el/com.aspose.slides/mathblock/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Καθορίζει μια παρουσία μαθηματικού κειμένου που περιέχεται σε ένα MathParagraph και ξεκινά σε δική του γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων εξισώσεων, εκφράσεων, σειρών εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBlock()](#MathBlock--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί το καθορισμένο στοιχείο σε αυτό. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί τα καθορισμένα στοιχεία σε αυτό. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των παιδικών στοιχείων μαθηματικού που περιέχονται στην συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Αξιωματική ή ορισμός του IMathElement στη συγκεκριμένη θέση. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Αξιωματική ή ορισμός του IMathElement στη συγκεκριμένη θέση. |
| [isReadOnly()](#isReadOnly--) | Επιστρέφει false επειδή η συλλογή των παιδικών στοιχείων μπορεί να τροποποιηθεί. |
| [getChildren()](#getChildren--) | Λαμβάνει τα παιδικά στοιχεία |
| [getParent_Immediate()](#getParent-Immediate--) | Επιστρέφει το αντικείμενο Parent\_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Προσθέτει ένα στοιχείο μαθηματικού στο τέλος της συλλογής. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Αντιγραφή σε καθορισμένο πίνακα. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Καθορίζει τον δείκτη ενός συγκεκριμένου στοιχείου μαθηματικού στη συλλογή. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Εισάγει ένα MathElement στη συλλογή στη συγκεκριμένη θέση. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό block |
| [join(String mathText)](#join-java.lang.String-) | Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό block |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Συνδέει ένα άλλο μαθηματικό block με αυτό |
| [delimit(char separatorCharacter)](#delimit-char-) | Οριοθετεί τα παιδικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Περιβάλλει τα παιδικά στοιχεία αυτού του block με καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλα ως πλαίσιο |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Περιβάλλει τα παιδικά στοιχεία αυτού του block με καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλα ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωριστή |
| [toMathArray()](#toMathArray--) | Τοποθετεί τα παιδικά στοιχεία σε κατακόρυφο πίνακα |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο αυτού του [MathBlock](../../com.aspose.slides/mathblock) ως MathML |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathBlock.

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

Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί το καθορισμένο στοιχείο σε αυτό.

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

Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί τα καθορισμένα στοιχεία σε αυτό.

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

Λαμβάνει τον αριθμό των παιδικών στοιχείων μαθηματικού που περιέχονται στην συλλογή. Μόνο για ανάγνωση int.

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

Αξιωματική ή ορισμός του IMathElement στη συγκεκριμένη θέση.

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
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement) - Το μαθηματικό στοιχείο.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Αξιωματική ή ορισμός του IMMathElement στη συγκεκριμένη θέση.

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
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Το μαθηματικό στοιχείο. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Επιστρέφει false επειδή η συλλογή των παιδικών στοιχείων μπορεί να τροποποιηθεί.

**Επιστρέφει:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει τα παιδικά στοιχεία

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent\_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Προσθέτει ένα στοιχείο μαθηματικού στο τέλος της συλλογής.

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το αντικείμενο που εντοπίζεται στη συλλογή. |

**Επιστρέφει:**
boolean - true αν το αντικείμενο βρεθεί στη συλλογή· αλλιώς false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Αντιγραφή σε καθορισμένο πίνακα.

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
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Πίνακας στον οποίο θα γίνει η αντιγραφή. |
| arrayIndex | int | Δείκτης από όπου αρχίζει η αντιγραφή. |

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
boolean - true αν το αντικείμενο αφαιρεθεί με επιτυχία· αλλιώς false. Η μέθοδος επιστρέφει επίσης false αν το αντικείμενο δεν βρεθεί στην αρχική συλλογή.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Επιστρέφει έναν enumerator που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Έναν IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.IEnumerator - Έναν java.util.Iterator για ολόκληρη τη συλλογή.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Καθορίζει τον δείκτη ενός συγκεκριμένου στοιχείου μαθηματικού στη συλλογή.

--------------------

> ```
> Example:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο που εντοπίζεται στη συλλογή. |

**Επιστρέφει:**
int - Ο δείκτης του αντικειμένου αν βρεθεί στη συλλογή· αλλιώς -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Εισάγει ένα MathElement στη συλλογή στη συγκεκριμένη θέση.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στο οποίο θα εισαχθεί το MathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Το MathElement που θα εισαχθεί. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής.

--------------------

> ```
> Example:
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
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό block

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο που θα συνδεθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Το τρέχον στιγμιότυπο του IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό block

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | java.lang.String | Μαθηματικό κείμενο που θα συνδεθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ένα νέο IMathBlock που περιέχει αυτό το στιγμιότυπο και το καθορισμένο όρισμα
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Συνδέει ένα άλλο μαθηματικό block με αυτό

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Το block που συνδέεται |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Αυτό το μαθηματικό block μετά τη σύνδεση
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Οριοθετεί τα παιδικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char | Χαρακτήρας διαχωριστή |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το στοιχείο μαθηματικού τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Περιβάλλει τα παιδικά στοιχεία αυτού του block με καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλα ως πλαίσιο

--------------------

> ```
> Example:
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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το στοιχείο μαθηματικού τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Περιβάλλει τα παιδικά στοιχεία αυτού του block με καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλα ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωριστή

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |
| separatorCharacter | char | Χαρακτήρας διαχωριστή |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το στοιχείο μαθηματικού τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο και διαχωριστή
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Τοποθετεί τα παιδικά στοιχεία σε κατακόρυφο πίνακα

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Επιστρέφει:**
[IMathArray](../../com.aspose.slides/imatharray) - Νέα εμφάνιση τύπου [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο αυτού του [MathBlock](../../com.aspose.slides/mathblock) ως MathML

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Στοχευόμενο ρεύμα |