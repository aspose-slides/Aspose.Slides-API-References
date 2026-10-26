---
title: IMathFraction
second_title: Aspose.Slides για Αναφορά API Java
description: Καθορίζει το αντικείμενο κλάσματος που αποτελείται από αριθμητή και παρανομαστή χωρισμένα με γραμμή κλάσματος.
type: docs
url: /el/com.aspose.slides/imathfraction/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Καθορίζει το αντικείμενο κλάσματος, που αποτελείται από αριθμητή και παρανομαστή χωρισμένα με γραμμή κλάσματος. Η γραμμή κλάσματος μπορεί να είναι οριζόντια ή διαγώνια, ανάλογα με τις ιδιότητες του κλάσματος. Το αντικείμενο κλάσματος χρησιμοποιείται επίσης για την παράσταση της συνάρτησης στοίβας, η οποία τοποθετεί ένα στοιχείο πάνω από ένα άλλο, χωρίς γραμμή κλάσματος.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFractionType()](#getFractionType--) | Τύπος κλάσματος Προεπιλογή: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Τύπος κλάσματος Προεπιλογή: Bar |
| [getNumerator()](#getNumerator--) | Αριθμητής |
| [getDenominator()](#getDenominator--) | Παρονομαστής |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
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
public abstract void setFractionType(int value)
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
public abstract IMathElement getNumerator()
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
public abstract IMathElement getDenominator()
```


Παρανομαστής

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)