---
title: MathNaryOperator
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Καθορίζει ένα N-ary μαθηματικό αντικείμενο όπως το Άθροισμα και το Ολοκλήρωμα.
type: docs
url: /el/com.aspose.slides/mathnaryoperator/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Καθορίζει ένα N-ary μαθηματικό αντικείμενο, όπως το Άθροισμα και το Ολοκλήρωμα. Αποτελείται από έναν τελεστή, μια βάση (ή όρο), και προαιρετικά άνω και κάτω όρια. Παραδείγματα N-ary τελεστών είναι: Άθροισμα, Ένωση, Τομή, Ολοκλήρωμα

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασική παράμετρος |
| [getSubscript()](#getSubscript--) | Καθορίζει ένα υποσκοπικό επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το κάτω όριο |
| [getSuperscript()](#getSuperscript--) | Καθορίζει ένα υπερσκοπικό επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο |
| [getOperator()](#getOperator--) | Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Η θέση των ορίων (υποσκοπικό και υπερσκοπικό) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Η θέση των ορίων (υποσκοπικό και υπερσκοπικό) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστέου |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστέου |
| [getHideSubscript()](#getHideSubscript--) | Απόκρυψη Υποσκοπικού |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Απόκρυψη Υποσκοπικού |
| [getHideSuperscript()](#getHideSuperscript--) | Απόκρυψη Υπερσκοπικού |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Απόκρυψη Υπερσκοπικού |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες ελέγχου χαρακτήρων |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Σύμβολο Nary τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασική παράμετρος |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Άνω όριο |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Σύμβολο Nary τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασική παράμετρος |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Σύμβολο Nary τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασική παράμετρος |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Βασική παράμετρος

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Καθορίζει ένα υποσκοπικό επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το κάτω όριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Καθορίζει ένα υπερσκοπικό επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Επιστρέφει:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

Η θέση των ορίων (υποσκοπικό και υπερσκοπικό)

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Επιστρέφει:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

Η θέση των ορίων (υποσκοπικό και υπερσκοπικό)

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστέου

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Επιστρέφει:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστέου

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

Απόκρυψη Υποσκοπικού

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Επιστρέφει:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

Απόκρυψη Υποσκοπικού

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

Απόκρυψη Υπερσκοπικού

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Επιστρέφει:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

Απόκρυψη Υπερσκοπικού

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ανάκτηση στοιχείων παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες ελέγχου χαρακτήρων

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps