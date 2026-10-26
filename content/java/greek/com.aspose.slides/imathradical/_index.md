---
title: IMathRadical
second_title: Αναφορά API του Aspose.Slides για Java
description: Καθορίζει τη ριζική λειτουργία που αποτελείται από μια βάση και έναν προαιρετικό βαθμό.
type: docs
url: /el/com.aspose.slides/imathradical/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Καθορίζει τη ριζική λειτουργία, που αποτελείται από μια βάση και έναν προαιρετικό βαθμό. Παράδειγμα ριζικού αντικειμένου είναι \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // κυβική ρίζα
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Ορίσμα βάσης |
| [getDegree()](#getDegree--) | Ορίσμα βαθμού |
| [getHideDegree()](#getHideDegree--) | Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Ορίσμα βάσης

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // κυβική ρίζα
>  IMathElement baseElem = radical.getBase();
>  ```


**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```

Ορίσμα βαθμού

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // κυβική ρίζα
>  IMathElement degreeElem = radical.getDegree();
>  ```


**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMMathRadical radical = new MathematicalText("x").radical("3"); // κυβική ρίζα
>  radical.setHideDegree(true);
>  ```


**Επιστρέφει:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

Απόκρυψη βαθμού. Όταν είναι true, ο βαθμός δεν εμφανίζεται, όπως στο \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |