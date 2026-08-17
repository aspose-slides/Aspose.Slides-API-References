---
title: IMathNaryOperator
second_title: Aspose.Slides για την Αναφορά API της Java
description: Καθορίζει ένα N-ary μαθηματικό αντικείμενο όπως Άθροιση και Ολοκλήρωμα.
type: docs
url: /el/com.aspose.slides/imathnaryoperator/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Καθορίζει ένα N-ary μαθηματικό αντικείμενο, όπως Summation και Integral. Αποτελείται από έναν τελεστή, μια βάση (ή όρο), και προαιρετικά άνω και κατώ τα όρια. Παραδείγματα N-ary τελεστών είναι: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Όρισμα βάσης |
| [getSubscript()](#getSubscript--) | Καθορίζει ένα επιχείρημα υποδείκτη που, για παράδειγμα, στη περίπτωση ενός integral, ορίζει το κατώτερο όριο |
| [getSuperscript()](#getSuperscript--) | Καθορίζει ένα επιχείρημα εκθέτη που, για παράδειγμα, στη περίπτωση ενός integral, ορίζει το ανώτερο όριο |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Όρισμα βάσης

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
public abstract IMathElement getSubscript()
```


Καθορίζει ένα επιχείρημα υποδείκτη που, για παράδειγμα, στη περίπτωση ενός integral, ορίζει το κατώτερο όριο

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
public abstract IMathElement getSuperscript()
```


Καθορίζει ένα επιχείρημα εκθέτη που, για παράδειγμα, στη περίπτωση ενός integral, ορίζει το ανώτερο όριο

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)