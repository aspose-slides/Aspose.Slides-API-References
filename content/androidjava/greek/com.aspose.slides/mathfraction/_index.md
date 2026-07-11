---
title: MathFraction
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Καθορίζει το αντικείμενο κλάσματος που αποτελείται από αριθμητή και παρονομαστή, χωρισμένους με μια γραμμή κλάσματος.
type: docs
url: /el/com.aspose.slides/mathfraction/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Καθορίζει το αντικείμενο κλάσματος, που αποτελείται από αριθμητή και παρονομαστή χωρισμένους από μια γραμμή κλάσματος. Η γραμμή κλάσματος μπορεί να είναι οριζόντια ή διαγώνια, ανάλογα με τις ιδιότητες του κλάσματος. Το αντικείμενο κλάσματος χρησιμοποιείται επίσης για την αναπαράσταση της συνάρτησης στοίβας, η οποία τοποθετεί ένα στοιχείο πάνω από ένα άλλο, χωρίς γραμμή κλάσματος.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Αρχικοποιεί το MathFraction με τον καθορισμένο αριθμητή, παρονομαστή και τύπο |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα MathFraction τύπου 'Bar' με τον καθορισμένο αριθμητή και παρονομαστή |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFractionType()](#getFractionType--) | Τύπος κλάσματος Προεπιλογή: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Τύπος κλάσματος Προεπιλογή: Bar |
| [getNumerator()](#getNumerator--) | Αριθμητής |
| [getDenominator()](#getDenominator--) | Παρονομαστής |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Αρχικοποιεί το MathFraction με τον καθορισμένο αριθμητή, παρονομαστή και τύπο

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Αριθμητής |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρονομαστής |
| fractionType | int | Τύπος κλάσματος |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Αρχικοποιεί ένα MathFraction τύπου 'Bar' με τον καθορισμένο αριθμητή και παρονομαστή

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Αριθμητής |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρονομαστής |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


Τύπος κλάσματος Προεπιλογή: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Επιστρέφει:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


Τύπος κλάσματος Προεπιλογή: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```


Αριθμητής

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Παρονομαστής

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
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