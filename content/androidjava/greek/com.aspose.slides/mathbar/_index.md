---
title: MathBar
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Καθορίζει τη λειτουργία μπάρας που αποτελείται από ένα βασικό όρισμα και μια γραμμή άνω ή κάτω
type: docs
url: /el/com.aspose.slides/mathbar/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Καθορίζει τη λειτουργία μπάρας, η οποία αποτελείται από ένα βασικό όρισμα και μια γραμμή πάνω ή κάτω

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Αρχικοποιεί το MathBar με γραμμή άνω (Θέση στην κορυφή) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Αρχικοποιεί το MathBar με καθορισμένη θέση |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getPosition()](#getPosition--) | Θέση της γραμμής της μπάρας. |
| [setPosition(int value)](#setPosition-int-) | Θέση της γραμμής της μπάρας. |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες χαρακτήρα ελέγχου |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

Αρχικοποιεί το MathBar με γραμμή άνω (Θέση στην κορυφή)

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
| position | int | Θέση της γραμμής της μπάρας. |

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

**Τιμή επιστροφής:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Θέση της γραμμής της μπάρας. Προεπιλογή: Κορυφή

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Τιμή επιστροφής:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Θέση της γραμμής της μπάρας. Προεπιλογή: Κορυφή

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

**Τιμή επιστροφής:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες χαρακτήρα ελέγχου

**Τιμή επιστροφής:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps