---
title: IMathNaryOperator
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Καθορίζει ένα Ν-αριακό μαθηματικό αντικείμενο όπως το Άθροισμα και το Ολοκλήρωμα.
type: docs
url: /el/com.aspose.slides/imathnaryoperator/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Καθορίζει ένα Ν-αριακό μαθηματικό αντικείμενο, όπως το Άθροισμα και το Ολοκλήρωμα. Αποτελείται από έναν τελεστή, μια βάση (ή τελεστέο) και προαιρετικά άνω και κάτω όρια. Παραδείγματα Ν-αριακών τελεστών είναι: Άθροισμα, Ένωση, Τομή, Ολοκλήρωμα

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit |
| [getSuperscript()](#getSuperscript--) | Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Βασικό όρισμα

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


Καθορίζει ένα υπό-δείκτη όρισμα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το κάτω όριο

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


Καθορίζει ένα υπέρ-δείκτη όρισμα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)