---
title: MathSuperscriptElement
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Καθορίζει το αντικείμενο εκθέτη που αποτελείται από μια βάση και έναν μικρότερου μεγέθους εκθέτη τοποθετημένο πάνω και δεξιά
type: docs
url: /el/com.aspose.slides/mathsuperscriptelement/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

Καθορίζει το αντικείμενο εκθέτη, το οποίο αποτελείται από μια βάση και έναν μικρότερου μεγέθους εκθέτη τοποθετημένο πάνω και δεξιά

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathSuperscriptElement. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | Εκθέτης |
| [getChildren()](#getChildren--) | Λαμβάνει τα στοιχεία παιδιών |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```

Αρχικοποιεί μια νέα παρουσία της κλάσης MathSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Εκθέτης

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει τα στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]