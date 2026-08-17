---
title: MathBox
second_title: Aspose.Slides για Java API Αναφορά
description: Καθορίζει τη λογική συσκευασία (boxing) ενός μαθηματικού στοιχείου.
type: docs
url: /el/com.aspose.slides/mathbox/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Καθορίζει τη λογική «συσκευασία» (boxing) μαθηματικού στοιχείου. Για παράδειγμα, ένα στοιχείο σε κουτί μπορεί να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να χρησιμεύει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπονται αλλαγές γραμμής εντός του. Για παράδειγμα, ο τελεστής «==» πρέπει να τοποθετηθεί σε κουτί για να αποτραπούν οι αλλαγές γραμμής.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Αρχικοποιεί το MathBox με το καθορισμένο στοιχείο ως όρισμα |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getOperatorEmulator()](#getOperatorEmulator--) | Προσομοιωτής τελεστή. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Προσομοιωτής τελεστή. |
| [getNoBreak()](#getNoBreak--) | Μη διακοπτόμενο Η ιδιότητα αυτή καθορίζει την «αδιάσπαστη» ιδιότητα στο αντικείμενο κουτί. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Μη διακοπτόμενο Η ιδιότητα αυτή καθορίζει την «αδιάσπαστη» ιδιότητα στο αντικείμενο κουτί. |
| [getDifferential()](#getDifferential--) | Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ. \\ud835\\udc51\\ud835\\udc65 σε ολοκλήρωμα) και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ. \\ud835\\udc51\\ud835\\udc65 σε ολοκλήρωμα) και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. |
| [getExplicitBreak()](#getExplicitBreak--) | Ρητή αλλαγή καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να "τυλίγεται" στην αρχή του αντικειμένου κουτί. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Ρητή αλλαγή καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να "τυλίγεται" στην αρχή του αντικειμένου κουτί. |
| [getChildren()](#getChildren--) | Λαμβάνει τα στοιχεία παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες ελέγχου χαρακτήρων |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Αρχικοποιεί το MathBox με το καθορισμένο στοιχείο ως όρισμα

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται το κουτί. Μπορεί να είναι null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Βασικό όρισμα

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Προσομοιωτής τελεστή. Όταν είναι true, το κουτί και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να χρησιμεύσει ως σημείο διακοπής γραμμής και να ευθυγραμμιστεί με άλλους τελεστές. Οι προσομοιωτές τελεστών χρησιμοποιούνται συχνά όταν ένας ή περισσότεροι γλύφοι συνδυάζονται για να σχηματίσουν τελεστή, όπως το '=='. Προεπιλεγμένη τιμή: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Επιστρέφει:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Προσομοιωτής τελεστή. Όταν είναι true, το κουτί και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να χρησιμεύσει ως σημείο διακοπής γραμμής και να ευθυγραμμιστεί με άλλους τελεστές. Οι προσομοιωτές τελεστών χρησιμοποιούνται συχνά όταν ένας ή περισσότεροι γλύφοι συνδυάζονται για να σχηματίσουν τελεστή, όπως το '=='. Προεπιλεγμένη τιμή: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Μη διακοπτόμενο Η ιδιότητα αυτή καθορίζει την «αδιάσπαστη» ιδιότητα στο αντικείμενο κουτί. Όταν είναι true, δεν μπορούν να εμφανιστούν αλλαγές γραμμής εντός του κουτιού. Αυτό μπορεί να είναι σημαντικό για προσομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικούς τελεστές. Όταν αυτό το στοιχείο δεν καθορίζεται, μπορούν να εμφανιστούν αλλαγές εντός του κουτιού. Προεπιλογή: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Επιστρέφει:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Μη διακοπτόμενο Η ιδιότητα αυτή καθορίζει την «αδιάσπαστη» ιδιότητα στο αντικείμενο κουτί. Όταν είναι true, δεν μπορούν να εμφανιστούν αλλαγές γραμμής εντός του κουτιού. Αυτό μπορεί να είναι σημαντικό για προσομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικούς τελεστές. Όταν αυτό το στοιχείο δεν καθορίζεται, μπορούν να εμφανιστούν αλλαγές εντός του κουτιού. Προεπιλογή: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ. \\ud835\\udc51\\ud835\\udc65 σε ολοκλήρωμα) και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλεγμένη τιμή: false

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
public final void setDifferential(boolean value)
```

Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ. \\ud835\\udc51\\ud835\\udc65 σε ολοκλήρωμα) και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλεγμένη τιμή: false

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
public final boolean getAlignmentPoint()
```

Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλεγμένη τιμή: false

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
public final void setAlignmentPoint(boolean value)
```

Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλεγμένη τιμή: false

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
public final byte getExplicitBreak()
```

Ρητή αλλαγή καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να «τυλίγεται» στην αρχή του αντικειμένου κουτί. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή του μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο στοίχισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255 Προεπιλογή: 0 (χωρίς ρητή αλλαγή)

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
public final void setExplicitBreak(byte value)
```

Ρητή αλλαγή καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να «τυλίγεται» στην αρχή του αντικειμένου κουτί. Καθορίζει τον αριθμό του τελεστή στη προηγούμενη γραμμή του μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο στοίχισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255 Προεπιλογή: 0 (χωρίς ρητή αλλαγή)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Αποκτά τα στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες ελέγχου χαρακτήρων

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps