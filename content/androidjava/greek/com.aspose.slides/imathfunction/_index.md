---
title: IMathFunction
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Καθορίζει μια συνάρτηση ενός ορίσματος.
type: docs
url: /el/com.aspose.slides/imathfunction/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Καθορίζει μια συνάρτηση ενός ορίσματος.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Όνομα λειτουργίας Για παράδειγμα, τα ονόματα λειτουργιών είναι sin και cos |
| [getBase()](#getBase--) | Ορίσμα λειτουργίας |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

Όνομα λειτουργίας Για παράδειγμα, τα ονόματα λειτουργιών είναι sin και cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Ορίσμα λειτουργίας

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)