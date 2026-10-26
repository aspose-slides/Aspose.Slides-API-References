---
title: MathNaryOperator
second_title: Αναφορά API Aspose.Slides για Java
description: Καθορίζει ένα N-αριθμητικό μαθηματικό αντικείμενο όπως το Άθροισμα και το Ολοκλήρωμα.
type: docs
url: /el/com.aspose.slides/mathnaryoperator/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλοι οι Υλοποιημένοι Διεπαφές:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Καθορίζει ένα N-ary μαθηματικό αντικείμενο, όπως το Άθροισμα και το Ολοκλήρωμα. Αποτελείται από έναν τελεστή, μια βάση (ή τελεστέο) και προαιρετικά άνω και κάτω όρια. Παραδείγματα N-ary τελεστών είναι: Άθροισμα, Ένωση, Τομή, Ολοκλήρωση

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathNaryOperator. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό επιχείρημα |
| [getSubscript()](#getSubscript--) | Καθορίζει ένα υποσυντελεστή επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, θέτει το κάτω όριο |
| [getSuperscript()](#getSuperscript--) | Καθορίζει ένα υπερσυντελεστή επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, θέτει το άνω όριο |
| [getOperator()](#getOperator--) | Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Η θέση των ορίων (υποσυντελεστή και υπερσυντελεστή) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Η θέση των ορίων (υποσυντελεστή και υπερσυντελεστή) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Ο χαρακτήρας του τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεστέου |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Ο χαρακτήρας του τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεστέου |
| [getHideSubscript()](#getHideSubscript--) | Απόκρυψη Υποσυντελεστή |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Απόκρυψη Υποσυντελεστή |
| [getHideSuperscript()](#getHideSuperscript--) | Απόκρυψη Υπερσυντελεστή |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Απόκρυψη Υπερσυντελεστή |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης MathNaryOperator.

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
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό επιχείρημα |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Άνω όριο |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Σύμβολο Nary τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό επιχείρημα |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Σύμβολο Nary τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό επιχείρημα |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Βασικό επιχείρημα

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


Καθορίζει ένα υποσυντελεστή επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, θέτει το κάτω όριο

--------------------

> ```
> Example:
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


Καθορίζει ένα υπερσυντελεστή επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, θέτει το άνω όριο

--------------------

> ```
> Example:
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


Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
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


Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
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


Η θέση των ορίων (υποσυντελεστή και υπερσυντελεστή)

--------------------

> ```
> Example:
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


Η θέση των ορίων (υποσυντελεστή και υπερσυντελεστή)

--------------------

> ```
> Example:
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


Ο χαρακτήρας του τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεστέου

--------------------

> ```
> Example:
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


Ο χαρακτήρας του τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεστέου

--------------------

> ```
> Example:
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


Απόκρυψη Υποσυντελεστή

--------------------

> ```
> Example:
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


Απόκρυψη Υποσυντελεστή

--------------------

> ```
> Example:
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


Απόκρυψη Υπερσυντελεστή

--------------------

> ```
> Example:
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


Απόκρυψη Υπερσυντελεστή

--------------------

> ```
> Example:
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


Λήψη στοιχείων παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Ιδιότητες Χαρακτήρων Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps