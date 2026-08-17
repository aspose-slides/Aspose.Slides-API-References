---
title: MathGroupingCharacter
second_title: Aspose.Slides για Java API Αναφορά
description: Καθορίζει ένα σύμβολο ομαδοποίησης πάνω ή κάτω από μια έκφραση, συνήθως για να τονίσει τη σχέση μεταξύ των στοιχείων
type: docs
url: /el/com.aspose.slides/mathgroupingcharacter/
---
**Κληρονομικότητα:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Καθορίζει ένα σύμβολο ομαδοποίησης πάνω ή κάτω από μια έκφραση, συνήθως για να τονίσει τη σχέση μεταξύ των στοιχείων

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο παράδειγμα της MathGroupingCharacter κλάσης με το προεπιλεγμένο σύμβολο ομαδοποίησης U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Αρχικοποιεί ένα νέο παράδειγμα της MathGroupingCharacter κλάσης. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getCharacter()](#getCharacter--) | Σύμβολο Ομαδοποίησης Προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Σύμβολο Ομαδοποίησης Προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Θέση του συμβόλου ομαδοποίησης. |
| [setPosition(int value)](#setPosition-int-) | Θέση του συμβόλου ομαδοποίησης. |
| [getVerticalJustification()](#getVerticalJustification--) | Κατακόρυφη στοίχιση του συμβόλου ομαδοποίησης. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Κατακόρυφη στοίχιση του συμβόλου ομαδοποίησης. |
| [getChildren()](#getChildren--) | Λήψη παιδικών στοιχείων |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρα Ελέγχου |

### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

Αρχικοποιεί ένα νέο παράδειγμα της MathGroupingCharacter κλάσης με το προεπιλεγμένο σύμβολο ομαδοποίησης U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται η γραμμή |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Αρχικοποιεί ένα νέο παράδειγμα της MathGroupingCharacter κλάσης.

--------------------

> ```
> Παράδειγμα:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται η γραμμή |
| character | char | Σύμβολο Ομαδοποίησης |
| position | int | Θέση του συμβόλου ομαδοποίησης |
| verticalJustification | int | Κατακόρυφη στοίχιση του συμβόλου ομαδοποίησης |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Βασικό όρισμα

--------------------

> ```
> Παράδειγμα:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Σύμβολο Ομαδοποίησης Προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Κάτω Παρένθεση
> ```

**Επιστρέφει:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Σύμβολο Ομαδοποίησης Προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Κάτω Παρένθεση
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Θέση του συμβόλου ομαδοποίησης. Προεπιλογή: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Θέση του συμβόλου ομαδοποίησης. Προεπιλογή: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

Κατακόρυφη στοίχιση του συμβόλου ομαδοποίησης. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν το σύμβολο ομαδοποίησης είναι πάνω από το αντικείμενο, η Κατακόρυφη Στοίχιση Top σημαίνει ότι το πάνω μέρος του αντικειμένου βρίσκεται στην γραμμή βάσης· όταν η Κατακόρυφη Στοίχιση οριστεί σε Bottom, το κάτω μέρος του αντικειμένου είναι στην γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Επιστρέφει:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

Κατακόρυφη στοίχιση του συμβόλου ομαδοποίησης. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν το σύμβολο ομαδοποίησης είναι πάνω από το αντικείμενο, η Κατακόρυφη Στοίχιση Top σημαίνει ότι το πάνω μέρος του αντικειμένου βρίσκεται στην γραμμή βάσης· όταν η Κατακόρυφη Στοίχιση οριστεί σε Bottom, το κάτω μέρος του αντικειμένου είναι στην γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λήψη παιδικών στοιχείων

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες Χαρακτήρα Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps