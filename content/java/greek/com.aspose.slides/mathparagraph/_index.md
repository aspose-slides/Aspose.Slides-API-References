---
title: MathParagraph
second_title: Aspose.Slides για Java API Αναφορά
description: Μαθηματική παράγραφος που είναι υποδοχέας για μαθηματικά μπλοκ IMathBlock
type: docs
url: /el/com.aspose.slides/mathparagraph/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Μαθηματική παράγραφος που είναι ένας υποδοχέας για μαθηματικά μπλοκ (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | Αρχικοποιεί μία νέα παρουσία της κλάσης MathParagraph. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | Αρχικοποιεί μία νέα παρουσία της κλάσης MathParagraph. |
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Default value: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Default value: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Επιστρέφει το αντικείμενο Parent_Immediate. |
| [getCount()](#getCount--) | Αποκτά τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στο συγκεκριμένο δείκτη. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Αποκτά το στοιχείο στο συγκεκριμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | Προσθέτει IMathBlock στο τέλος της συλλογής. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Καθορίζει αν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Καθορίζει το δείκτη ενός συγκεκριμένου IMathBlock στη συλλογή. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | Εισάγει IMathBlock στη συλλογή στο συγκεκριμένο δείκτη. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα στοιχείο στο συγκεκριμένο δείκτη της συλλογής. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο αυτού [MathParagraph](../../com.aspose.slides/mathparagraph) ως MathML |
| [toLatex()](#toLatex--) | Αποκτά μαθηματική εξίσωση σε μορφή LaTeX |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```


Αρχικοποιεί μία νέα παρουσία της κλάσης MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```


Αρχικοποιεί μία νέα παρουσία της κλάσης MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```


Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Επιστρέφει:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```


Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```


Αποκτά τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```


Αποκτά το στοιχείο στο συγκεκριμένο δείκτη. Μόνο για ανάγνωση [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσης μηδέν του στοιχείου που θα ληφθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Το μπλοκ ενός μαθηματικού κειμένου.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```


Αποκτά το στοιχείο στο συγκεκριμένο δείκτη. Μόνο για ανάγνωση [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσης μηδέν του στοιχείου που θα ληφθεί |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Το μπλοκ ενός μαθηματικού κειμένου. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```


Προσθέτει IMathBlock στο τέλος της συλλογής.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Ένα μαθηματικό μπλοκ που θα προστεθεί στο τέλος της συλλογής |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Το αντικείμενο που θα αφαιρεθεί από τη συλλογή. |

**Επιστρέφει:**
boolean - true αν το mathBlock αφαιρέθηκε επιτυχώς από τη συλλογή· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false αν το mathBlock δεν βρεθεί στην αρχική συλλογή.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```


Καθορίζει αν η συλλογή περιέχει μια συγκεκριμένη τιμή.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Το αντικείμενο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
boolean - true αν το mathBlock βρεθεί στη συλλογή· διαφορετικά, false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```


Καθορίζει το δείκτη ενός συγκεκριμένου IMMathBlock στη συλλογή.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Το στοιχείο που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Το δείκτη του mathBlock αν βρεθεί στη συλλογή· διαφορετικά, -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```


Εισάγει IMathBlock στη συλλογή στο συγκεκριμένο δείκτη.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσης μηδέν στο οποίο θα εισαχθεί ένα στοιχείο. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Το IMathBlock που θα εισαχθεί. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί ένα στοιχείο στο συγκεκριμένο δείκτη της συλλογής.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσης μηδέν του στοιχείου που θα αφαιρεθεί. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```




**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```




**Επιστρέφει:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


Αποθηκεύει το περιεχόμενο αυτού [MathParagraph](../../com.aspose.slides/mathparagraph) ως MathML

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή-στόχος |

### toLatex() {#toLatex--}
```
public final String toLatex()
```


Αποκτά μαθηματική εξίσωση σε μορφή LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Επιστρέφει:**
java.lang.String