---
title: MathBar
second_title: Aspose.Slides για Java API Αναφορά
description: Καθορίζει τη λειτουργία της μπάρας που αποτελείται από ένα βασικό όρισμα και μια πάνω ή κάτω μπάρα
type: docs
url: /el/com.aspose.slides/mathbar/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Καθορίζει τη λειτουργία της μπάρας, η οποία αποτελείται από ένα βασικό όρισμα και μια μπάρα πάνω ή κάτω

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Αρχικοποιεί το MathBar με πάνω μπάρα (Θέση Κορυφή) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Αρχικοποιεί το MathBar με καθορισμένη θέση |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getPosition()](#getPosition--) | Θέση της μπάρας. |
| [setPosition(int value)](#setPosition-int-) | Θέση της μπάρας. |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


Αρχικοποιεί το MathBar με πάνω μπάρα (Θέση Κορυφή)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται η μπάρα |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


Αρχικοποιεί το MathBar με καθορισμένη θέση

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται η μπάρα |
| position | int | Θέση της μπάρας. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Βασικό όρισμα

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Θέση της μπάρας. Προεπιλογή: Κορυφή

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Θέση της μπάρας. Προεπιλογή: Κορυφή

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λήψη στοιχείων παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Ιδιότητες Χαρακτήρων Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps