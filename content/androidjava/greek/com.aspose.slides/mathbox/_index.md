---
title: MathBox
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Καθορίζει το λογικό καδράρισμα (συσκευασία) μαθηματικού στοιχείου.
type: docs
url: /el/com.aspose.slides/mathbox/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Καθορίζει το λογικό καδράρισμα (συσκευασία) μαθηματικού στοιχείου. Για παράδειγμα, ένα καδράρισμένο αντικείμενο μπορεί να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργεί ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπεται η αλλαγή γραμμής εντός του. Για παράδειγμα, ο τελεστής "==" πρέπει να είναι καδράριστος ώστε να αποτρέπονται οι αλλαγές γραμμής.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Κατασκευές

| Κατασκευή | Περιγραφή |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Αρχικοποιεί το MathBox με το καθορισμένο στοιχείο ως όρισμα |
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getOperatorEmulator()](#getOperatorEmulator--) | Προσομοιωτής τελεστή. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Προσομοιωτής τελεστή. |
| [getNoBreak()](#getNoBreak--) | Χωρίς διακοπή Αυτή η ιδιότητα καθορίζει την ιδιότητα "unbreakable" στο κουτί αντικειμένου. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Χωρίς διακοπή Αυτή η ιδιότητα καθορίζει την ιδιότητα "unbreakable" στο κουτί αντικειμένου. |
| [getDifferential()](#getDifferential--) | Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να στοιχιστούν με αυτό. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να στοιχιστούν με αυτό. |
| [getExplicitBreak()](#getExplicitBreak--) | Ρητή αλλαγή γραμμής καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Ρητή αλλαγή γραμμής καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου box. |
| [getChildren()](#getChildren--) | Λαμβάνει στοιχεία παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες χαρακτήρα ελέγχου |
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
| Παράμετρος | Type | Περιγραφή |
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

Προσομοιωτής τελεστή. Όταν είναι true, το κουτί και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργήσει ως σημείο αλλαγής γραμμής και μπορεί να στοιχιστεί με άλλους τελεστές. Οι προσομοιωτές τελεστή χρησιμοποιούνται συχνά όταν ένα ή περισσότερα γλύφη συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως '=='. Προεπιλεγμένη τιμή: false

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

Προσομοιωτής τελεστή. Όταν είναι true, το κουτί και τα περιεχόμενά του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργήσει ως σημείο αλλαγής γραμμής και μπορεί να στοιχιστεί με άλλους τελεστές. Οι προσομοιωτές τελεστή χρησιμοποιούνται συχνά όταν ένα ή περισσότερα γλύφη συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως '=='. Προεπιλεγμένη τιμή: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Χωρίς διακοπή Αυτή η ιδιότητα καθορίζει την ιδιότητα "unbreakable" στο κουτί αντικειμένου. Όταν είναι true, δεν μπορούν να εμφανιστούν αλλαγές γραμμής εντός του κουτιού. Αυτό μπορεί να είναι σημαντικό για προσομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθορίζεται, μπορούν να εμφανιστούν αλλαγές μέσα στο κουτί. Προεπιλογή: true

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

Χωρίς διακοπή Αυτή η ιδιότητα καθορίζει την ιδιότητα "unbreakable" στο κουτί αντικειμένου. Όταν είναι true, δεν μπορούν να εμφανιστούν αλλαγές γραμμής εντός του κουτιού. Αυτό μπορεί να είναι σημαντικό για προσομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθορίζεται, μπορούν να εμφανιστούν αλλαγές μέσα στο κουτί. Προεπιλογή: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλογή: false

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

Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\ud835\\udc51\\ud835\\udc65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλογή: false

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
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να στοιχιστούν με αυτό. Προεπιλογή: false

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

Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να στοιχιστούν με αυτό. Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

Ρητή αλλαγή γραμμής καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου box. Καθορίζει τον αριθμό του τελεστή στην προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο στοίχισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255 Προεπιλογή: 0 (χωρίς ρητή αλλαγή γραμμής)

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

Ρητή αλλαγή γραμμής καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου box. Καθορίζει τον αριθμό του τελεστή στην προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο στοίχισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255 Προεπιλογή: 0 (χωρίς ρητή αλλαγή γραμμής)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες χαρακτήρα ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps