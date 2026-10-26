---
title: IMathBox
second_title: Αναφορά API Aspose.Slides για Java
description: Καθορίζει τη λογική συσκευασία (boxing) του μαθηματικού στοιχείου.
type: docs
url: /el/com.aspose.slides/imathbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Καθορίζει τη λογική συσκευασία (packaging) του μαθηματικού στοιχείου. Για παράδειγμα, ένα συσκευασμένο αντικείμενο μπορεί να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπεται η αλλαγή γραμμής εντός. Για παράδειγμα, ο τελεστής "==" πρέπει να συσκευαστεί για να αποτραπούν οι αλλαγές γραμμής.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασική παράμετρος |
| [getOperatorEmulator()](#getOperatorEmulator--) | Εξομοιωτής τελεστή. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Εξομοιωτής τελεστή. |
| [getNoBreak()](#getNoBreak--) | Χωρίς διάλειμμα. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Χωρίς διάλειμμα. |
| [getDifferential()](#getDifferential--) | Διαφορικό. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Διαφορικό. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Όταν είναι αληθής, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Όταν είναι αληθής, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. |
| [getExplicitBreak()](#getExplicitBreak--) | Η ρητή αλλαγή καθορίζει εάν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να αναδιπλώνεται στην αρχή του αντικειμένου box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Η ρητή αλλαγή καθορίζει εάν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να αναδιπλώνεται στην αρχή του αντικειμένου box. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Βασική παράμετρος

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

Εξομοιωτής τελεστή. Όταν είναι αληθής, το πλαίσιο και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργήσει ως σημείο αλλαγής γραμμής και να ευθυγραμμιστεί με άλλους τελεστές. Οι εξομοιωτές τελεστή χρησιμοποιούνται συχνά όταν ένα ή περισσότερα γλυφά συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως το '=='. Προεπιλεγμένη τιμή: false

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

Εξομοιωτής τελεστή. Όταν είναι αληθής, το πλαίσιο και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργήσει ως σημείο αλλαγής γραμμής και να ευθυγραμμιστεί με άλλους τελεστές. Οι εξομοιωτές τελεστή χρησιμοποιούνται συχνά όταν ένα ή περισσότερα γλυφά συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως το '=='. Προεπιλεγμένη τιμή: false

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

Χωρίς διάλειμμα. Αυτή η ιδιότητα καθορίζει την ιδιότητα "unbreakable" στο αντικείμενο box. Όταν είναι αληθής, δεν μπορούν να συμβούν αλλαγές γραμμής εντός του box. Αυτό μπορεί να είναι σημαντικό για εξομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθορίζεται, μπορούν να συμβούν αλλαγές εντός του box. Προεπιλεγμένη τιμή: true

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

Χωρίς διάλειμμα. Αυτή η ιδιότητα καθορίζει την ιδιότητα "unbreakable" στο αντικείμενο box. Όταν είναι αληθής, δεν μπορούν να συμβούν αλλαγές γραμμής εντός του box. Αυτό μπορεί να είναι σημαντικό για εξομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθορίζεται, μπορούν να συμβούν αλλαγές εντός του box. Προεπιλεγμένη τιμή: true

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

Διαφορικό. Όταν είναι αληθής, το πλαίσιο λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο) και λαμβάνει το κατάλληλο οριζόντιο κενό για το μαθηματικό διαφορικό. Προεπιλεγμένη τιμή: false

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

Διαφορικό. Όταν είναι αληθής, το πλαίσιο λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο) και λαμβάνει το κατάλληλο οριζόντιο κενό για το μαθηματικό διαφορικό. Προεπιλεγμένη τιμή: false

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

Όταν είναι αληθής, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλεγμένη τιμή: false

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

Όταν είναι αληθής, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλεγμένη τιμή: false

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

Η ρητή αλλαγή καθορίζει εάν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να αναδιπλώνεται στην αρχή του αντικειμένου box. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255. Προεπιλεγμένη τιμή: 0 (χωρίς ρητή αλλαγή)

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

Η ρητή αλλαγή καθορίζει εάν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να αναδιπλώνεται στην αρχή του αντικειμένου box. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255. Προεπιλεγμένη τιμή: 0 (χωρίς ρητή αλλαγή)

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