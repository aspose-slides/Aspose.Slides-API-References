---
title: IMathBar
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Καθορίζει τη συνάρτηση bar η οποία αποτελείται από ένα βασικό όρισμα και μια γραμμή πάνω ή κάτω
type: docs
url: /el/com.aspose.slides/imathbar/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Καθορίζει τη συνάρτηση bar, η οποία αποτελείται από ένα βασικό όρισμα και μια γραμμή πάνω ή κάτω

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getPosition()](#getPosition--) | Θέση της γραμμής. |
| [setPosition(int value)](#setPosition-int-) | Θέση της γραμμής. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Βασικό όρισμα

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Θέση της γραμμής. Προεπιλογή: Πάνω

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Θέση της γραμμής. Προεπιλογή: Πάνω

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |