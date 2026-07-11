---
title: MathSubscriptElement
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Καθορίζει το αντικείμενο δείκτη το οποίο αποτελείται από μια βάση και έναν μειωμένου μεγέθους δείκτη τοποθετημένο κάτω και δεξιά.
type: docs
url: /el/com.aspose.slides/mathsubscriptelement/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Καθορίζει το αντικείμενο δείκτη, το οποίο αποτελείται από μια βάση και έναν μειωμένου μεγέθους δείκτη τοποθετημένο κάτω και δεξιά.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathSubscriptElement. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSubscript()](#getSubscript--) | Δείκτης |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathSubscriptElement.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Δείκτης

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λήψη στοιχείων παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]