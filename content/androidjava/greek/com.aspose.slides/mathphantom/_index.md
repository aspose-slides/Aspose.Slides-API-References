---
title: MathPhantom
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα φανταστικό μαθηματικό αντικείμενο ltmphantgt που επηρεάζει τη διάταξη του στοιχείου-παιδιού του χωρίς απαραίτητα να το εμφανίζει.
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

Αντιπροσωπεύει ένα φανταστικό μαθηματικό αντικείμενο (<m:phant>) που επηρεάζει τη διάταξη του στοιχείου-παιδιού του χωρίς απαραίτητα να το εμφανίζει. Ένα φανταστικό αντικείμενο μπορεί να κρύβει την βασική του έκφραση ενώ διατηρεί το πλάτος, το ύψος ή το βάθος του για να ευθυγραμμίσει τύπους ή να κρατήσει χώρο. Η ορατότητα και η γεωμετρική συμπεριφορά ελέγχονται από ιδιότητες όπως Show, ZeroWid, ZeroAsc, ZeroDesc και Transp.

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
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getShow()](#getShow--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται. |
| [setShow(boolean value)](#setShow-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται. |
| [getZeroWidth()](#getZeroWidth--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου πρέπει να θεωρείται μηδέν. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου πρέπει να θεωρείται μηδέν. |
| [getZeroAsc()](#getZeroAsc--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η άνοδος (υψόμετρο πάνω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η άνοδος (υψόμετρο πάνω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν. |
| [getZeroDesc()](#getZeroDesc--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν. |
| [getTransp()](#getTransp--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες απόστασης βάσει κλάσης. |
| [setTransp(boolean value)](#setTransp-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες απόστασης βάσει κλάσης. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρα Ελέγχου |
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
| Παραμέτρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό [IMathElement](../../com.aspose.slides/imathelement) του οποίου η ορατότητα και η διάταξη θα ελεγχθούν από το φανταστικό. Αυτό το στοιχείο ορίζει το περιεχόμενο που μπορεί να κρυφτεί ή να εμφανιστεί, ενώ εξακολουθεί να επηρεάζει τη γεωμετρική ευθυγράμμιση των γύρω μαθηματικών.

Το φανταστικό στοιχείο χρησιμοποιείται για να διατηρήσει ή να καταστέλλει τον οπτικό χώρο της βασικής του έκφρασης χωρίς απαραίτητη εμφάνιση. Αντιστοιχεί στο στοιχείο OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Βασικό όρισμα

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

Όταν είναι ψευδές, το βασικό στοιχείο είναι κρυμμένο αλλά μπορεί ακόμα να καταλαμβάνει χώρο ανάλογα με άλλες ρυθμίσεις του φανταστικού. Αντιστοιχεί στο χαρακτηριστικό OMML m:show.

**Επιστρέφει:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται.

--------------------

Όταν είναι ψευδές, το βασικό στοιχείο είναι κρυμμένο αλλά μπορεί ακόμα να καταλαμβάνει χώρο ανάλογα με άλλες ρυθμίσεις του φανταστικού. Αντιστοιχεί στο χαρακτηριστικό OMML m:show.

**Παράμετροι:**
| Παραμέτρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου πρέπει να θεωρείται μηδέν.

--------------------

Όταν είναι αληθές, το φανταστικό δεν διατηρεί οριζόντιο χώρο για το βασικό του στοιχείο. Αντιστοιχεί στο χαρακτηριστικό OMML m:zeroWid.

**Επιστρέφει:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου πρέπει να θεωρείται μηδέν.

--------------------

Όταν είναι αληθές, το φανταστικό δεν διατηρεί οριζόντιο χώρο για το βασικό του στοιχείο. Αντιστοιχεί στο χαρακτηριστικό OMML m:zeroWid.

**Παράμετροι:**
| Παραμέτρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η άνοδος (υψόμετρο πάνω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν.

--------------------

Όταν είναι αληθές, το φανταστικό δεν ανεβάζει τη βασική γραμμή της γύρω μαθηματικής γραμμής. Αντιστοιχεί στο χαρακτηριστικό OMML m:zeroAsc.

**Επιστρέφει:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η άνοδος (υψόμετρο πάνω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν.

--------------------

Όταν είναι αληθές, το φανταστικό δεν ανεβάζει τη βασική γραμμή της γύρω μαθηματικής γραμμής. Αντιστοιχεί στο χαρακτηριστικό OMML m:zeroAsc.

**Παράμετροι:**
| Παραμέτρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν.

--------------------

Όταν είναι αληθές, το φανταστικό δεν χαμηλώνει τη βασική γραμμή της γύρω μαθηματικής γραμμής. Αντιστοιχεί στο χαρακτηριστικό OMML m:zeroDesc.

**Επιστρέφει:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η κάθοδος (βάθος κάτω από τη βασική γραμμή) του βασικού στοιχείου πρέπει να θεωρείται μηδέν.

--------------------

Όταν είναι αληθές, το φανταστικό δεν χαμηλώνει τη βασική γραμμή της γύρω μαθηματικής γραμμής. Αντιστοιχεί στο χαρακτηριστικό OMML m:zeroDesc.

**Παράμετροι:**
| Παραμέτρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες απόστασης βάσει κλάσης.

--------------------

Όταν είναι αληθές, οι τελεστές και τα σύμβολα μέσα στο φανταστικό εξακολουθούν να επηρεάζουν την μαθηματική απόσταση γύρω από το φανταστικό (σαν να είναι ορατό). Όταν είναι ψευδές, η απόσταση βάσει κλάσης αγνοείται. Αντιστοιχεί στο χαρακτηριστικό OMML m:transp.

**Επιστρέφει:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για τους κανόνες απόστασης βάσει κλάσης.

--------------------

Όταν είναι αληθές, οι τελεστές και τα σύμβολα μέσα στο φανταστικό εξακολουθούν να επηρεάζουν την μαθηματική απόσταση γύρω από το φανταστικό (σαν να είναι ορατό). Όταν είναι ψευδές, η απόσταση βάσει κλάσης αγνοείται. Αντιστοιχεί στο χαρακτηριστικό OMML m:transp.

**Παράμετροι:**
| Παραμέτρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες Χαρακτήρα Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει τα στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]