---
title: IMathBox
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Καθορίζει τη λογική συσκευασία (boxing) του μαθηματικού στοιχείου.
type: docs
url: /el/com.aspose.slides/imathbox/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Καθορίζει τη λογική περιτύλιξη (συσκευασία) μαθηματικού στοιχείου. Για παράδειγμα, ένα αντικείμενο Box μπορεί να λειτουργεί ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργεί ως σημείο διακοπής γραμμής ή να ομαδοποιείται ώστε να μην επιτρέπονται διακοπές γραμμής εντός του. Για παράδειγμα, ο τελεστής "==" πρέπει να περιτυλιχτεί για να αποτραπούν διακοπές γραμμής.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό επιχείρημα |
| [getOperatorEmulator()](#getOperatorEmulator--) | Εξομοιωτής τελεστή. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Εξομοιωτής τελεστή. |
| [getNoBreak()](#getNoBreak--) | Χωρίς διακοπή. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Χωρίς διακοπή. |
| [getDifferential()](#getDifferential--) | Διαφορικό. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Διαφορικό. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Όταν είναι true, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Όταν είναι true, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. |
| [getExplicitBreak()](#getExplicitBreak--) | Η ρητή διακοπή καθορίζει αν υπάρχει διακοπή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Η ρητή διακοπή καθορίζει αν υπάρχει διακοπή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Βασικό επιχείρημα

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```


**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Εξομοιωτής τελεστή. Όταν είναι true, το Box και το περιεχόμενό του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργεί ως σημείο διακοπής γραμμής και μπορεί να ευθυγραμμιστεί με άλλους τελεστές. Οι εξομοιωτές τελεστή χρησιμοποιούνται συχνά όταν ένα ή περισσότερα σύμβολα συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως το '==' . Προεπιλεγμένη τιμή: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Επιστρέφει:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Εξομοιωτής τελεστή. Όταν είναι true, το Box και το περιεχόμενό του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργεί ως σημείο διακοπής γραμμής και μπορεί να ευθυγραμμιστεί με άλλους τελεστές. Οι εξομοιωτές τελεστή χρησιμοποιούνται συχνά όταν ένα ή περισσότερα σύμβολα συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως το '==' . Προεπιλεγμένη τιμή: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Χωρίς διακοπή. Αυτή η ιδιότητα καθορίζει την ιδιότητα «αδιαίρετο» στο αντικείμενο Box. Όταν είναι true, δεν μπορούν να συμβούν διακοπές γραμμής εντός του Box. Αυτό μπορεί να είναι σημαντικό για εξομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθορίζεται, οι διακοπές μπορούν να συμβούν εντός του Box. Προεπιλογή: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Επιστρέφει:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Χωρίς διακοπή. Αυτή η ιδιότητα καθορίζει την ιδιότητα «αδιαίρετο» στο αντικείμενο Box. Όταν είναι true, δεν μπορούν να συμβούν διακοπές γραμμής εντός του Box. Αυτό μπορεί να είναι σημαντικό για εξομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθορίζεται, οι διακοπές μπορούν να συμβούν εντός του Box. Προεπιλογή: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Διαφορικό. Όταν είναι true, το Box λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστιχο για το μαθηματικό διαφορικό. Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Επιστρέφει:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Διαφορικό. Όταν είναι true, το Box λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστιχο για το μαθηματικό διαφορικό. Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Όταν είναι true, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Επιστρέφει:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Όταν είναι true, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Η ρητή διακοπή καθορίζει αν υπάρχει διακοπή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255. Προεπιλογή: 0 (χωρίς ρητή διακοπή)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Επιστρέφει:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Η ρητή διακοπή καθορίζει αν υπάρχει διακοπή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255. Προεπιλογή: 0 (χωρίς ρητή διακοπή)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |