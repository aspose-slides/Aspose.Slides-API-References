---
title: MathPhantom
second_title: Aspose.Slides για την αναφορά API Java
description: Αναπαριστά ένα φανταστικό μαθηματικό αντικείμενο ltmphantgt που επηρεάζει τη διάταξη του θυγατρικού του στοιχείου χωρίς απαραίτητα να το εμφανίζει.
type: docs
url: /el/com.aspose.slides/mathphantom/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Αναπαριστά ένα φανταστικό μαθηματικό αντικείμενο (<m:phant>) που επηρεάζει τη διάταξη του θυγατρικού του στοιχείου χωρίς απαραίτητα να το εμφανίζει. Ένα φανταστικό μπορεί να κρύβει την βασική έκφρασή του διατηρώντας το πλάτος, το ύψος ή το βάθος του για να ευθυγραμμίζει τύπους ή να κρατήσει χώρο. Η ορατότητα και η γεωμετρική συμπεριφορά ελέγχονται από ιδιότητες όπως Show, ZeroWid, ZeroAsc, ZeroDesc και Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Απόκρυψη του περιεχομένου
>  phantom.setZeroWidth(false);     // Διατήρηση του πλάτους
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MathPhantom](../../com.aspose.slides/mathphantom) χρησιμοποιώντας το καθορισμένο βασικό μαθηματικό στοιχείο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό επιχείρημα |
| [getShow()](#getShow--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται. |
| [setShow(boolean value)](#setShow-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται. |
| [getZeroWidth()](#getZeroWidth--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν. |
| [getZeroAsc()](#getZeroAsc--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η αναρρίχηση (υψόμετρο πάνω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η αναρρίχηση (υψόμετρο πάνω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν. |
| [getZeroDesc()](#getZeroDesc--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν. |
| [getTransp()](#getTransp--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες διαστήματος βάσει κλάσης. |
| [setTransp(boolean value)](#setTransp-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες διαστήματος βάσει κλάσης. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
| [getChildren()](#getChildren--) | Λαμβάνει τα στοιχεία παιδιών |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MathPhantom](../../com.aspose.slides/mathphantom) χρησιμοποιώντας το καθορισμένο βασικό μαθηματικό στοιχείο.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό [IMathElement](../../com.aspose.slides/imathelement) του οποίου η ορατότητα και η διάταξη θα ελεγχθούν από το φανταστικό. Αυτό το στοιχείο καθορίζει το περιεχόμενο που μπορεί να κρυφτεί ή να εμφανιστεί, ενώ εξακολουθεί να επηρεάζει τη γεωμετρική ευθυγράμμιση των γύρω μαθηματικών.

--------------------

Το φανταστικό στοιχείο χρησιμοποιείται για να διατηρήσει ή να καταστήσει μη ορατό το οπτικό χώρο της βασικής έκφρασης χωρίς απαραίτητα να το εμφανίζει. Αντιστοιχεί στο στοιχείο OMML <m:phant>. |
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Βασικό επιχείρημα

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**Επιστρέφει:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**Επιστρέφει:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η αναρρίχηση (υψόμετρο πάνω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**Επιστρέφει:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η αναρρίχηση (υψόμετρο πάνω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**Επιστρέφει:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βάση) του βασικού στοιχείου θα αντιμετωπιστεί ως μηδέν.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες διαστήματος βάσει κλάσης.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**Επιστρέφει:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες διαστήματος βάσει κλάσης.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες Χαρακτήρων Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει τα στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]