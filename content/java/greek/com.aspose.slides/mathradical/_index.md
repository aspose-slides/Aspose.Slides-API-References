---
title: MathRadical
second_title: Aspose.Slides για Java API Αναφορά
description: Καθορίζει τη ριζική συνάρτηση που αποτελείται από μια βάση και έναν προαιρετικό βαθμό.
type: docs
url: /el/com.aspose.slides/mathradical/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Καθορίζει τη ριζική συνάρτηση, που αποτελείται από βάση και προαιρετικό βαθμό. Παράδειγμα αντικειμένου ριζικής συνάρτησης είναι \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathRadical. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Ορίσμα βάσης |
| [getDegree()](#getDegree--) | Ορίσμα βαθμού |
| [getHideDegree()](#getHideDegree--) | Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
| [getChildren()](#getChildren--) | Λήψη στοιχείων θυγατρικών |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βάση |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βαθμός |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Ορίσμα βάσης

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```

Ορίσμα βαθμού

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```

Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Επιστρέφει:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```

Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες Χαρακτήρων Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λήψη στοιχείων θυγατρικών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]