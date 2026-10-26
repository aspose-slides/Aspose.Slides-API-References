---
title: IMathBar
second_title: Aspose.Slides για την Αναφορά API Java
description: Καθορίζει τη συνάρτηση bar που αποτελείται από ένα βασικό όρισμα και μια πάνω ή κάτω μπάρα
type: docs
url: /el/com.aspose.slides/imathbar/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Καθορίζει τη συνάρτηση bar, η οποία αποτελείται από ένα βασικό όρισμα και μια πάνω ή κάτω μπάρα

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getPosition()](#getPosition--) | Θέση της γραμμής μπάρας. |
| [setPosition(int value)](#setPosition-int-) | Θέση της γραμμής μπάρας. |
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

Θέση της γραμμής μπάρας. Προεπιλογή: Πάνω

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

Θέση της γραμμής μπάρας. Προεπιλογή: Πάνω

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
| value | int |  |