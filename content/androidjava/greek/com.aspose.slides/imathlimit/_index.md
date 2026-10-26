---
title: IMathLimit
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Καθορίζει το αντικείμενο Limit, το οποίο αποτελείται από κείμενο στη γραμμή βάσης και κείμενο μειωμένου μεγέθους ακριβώς πάνω ή κάτω από αυτό.
type: docs
url: /el/com.aspose.slides/imathlimit/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

Καθορίζει το αντικείμενο Limit, το οποίο αποτελείται από κείμενο στη γραμμή βάσης και κείμενο μειωμένου μεγέθους ακριβώς πάνω ή κάτω από αυτό.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Αρχικό όρισμα |
| [getLimit()](#getLimit--) | Όρισμα ορίου |
| [getUpperLimit()](#getUpperLimit--) | Καθορίζει άνω ή κάτω όριο |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Καθορίζει άνω ή κάτω όριο |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Αρχικό όρισμα

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```

Όρισμα ορίου

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```

Καθορίζει άνω ή κάτω όριο

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Επιστρέφει:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```

Καθορίζει άνω ή κάτω όριο

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |