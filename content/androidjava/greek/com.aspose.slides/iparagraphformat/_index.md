---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /el/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφου. Σε αντίθεση με [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

--------------------

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης παραγράφου που ορίζονται για τη συγκεκριμένη παράγραφο. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη των τιμών, έτσι στις περισσότερες περιπτώσεις θα λαμβάνετε τιμές που σημαίνουν «αόριστη».

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) η οποία επιστρέφει ένα παράδειγμα [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBullet()](#getBullet--) | Επιστρέφει τη μορφή κουκίδας της παραγράφου. |
| [getDepth()](#getDepth--) | Επιστρέφει ή ορίζει το βάθος της παραγράφου. |
| [setDepth(short value)](#setDepth-short-) | Επιστρέφει ή ορίζει το βάθος της παραγράφου. |
| [getAlignment()](#getAlignment--) | Επιστρέφει ή ορίζει τη στοίχιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setAlignment(int value)](#setAlignment-int-) | Επιστρέφει ή ορίζει τη στοίχιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getSpaceWithin()](#getSpaceWithin--) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [getSpaceBefore()](#getSpaceBefore--) | Επιστρέφει ή ορίζει το διάστημα πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Επιστρέφει ή ορίζει το διάστημα πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getSpaceAfter()](#getSpaceAfter--) | Επιστρέφει ή ορίζει το διάστημα μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Επιστρέφει ή ορίζει το διάστημα μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Καθορίζει αν η ανακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Καθορίζει αν η ανακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει αν η γραφή από δεξιά προς αριστερά χρησιμοποιείται σε μια παράγραφο. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Καθορίζει αν η γραφή από δεξιά προς αριστερά χρησιμοποιείται σε μια παράγραφο. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Καθορίζει αν η λατινική ανακοπή γραμμής χρησιμοποιείται σε μια παράγραφο. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Καθορίζει αν η λατινική ανακοπή γραμμής χρησιμοποιείται σε μια παράγραφο. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setMarginRight(float value)](#setMarginRight-float-) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getIndent()](#getIndent--) | Επιστρέφει ή ορίζει την πρώτη γραμμή εσοχής/κρεμαστής εσοχής της παραγράφου χωρίς κληρονομικότητα. |
| [setIndent(float value)](#setIndent-float-) | Επιστρέφει ή ορίζει την πρώτη γραμμή εσοχής/κρεμαστής εσοχής της παραγράφου χωρίς κληρονομικότητα. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής (tab) χωρίς κληρονομικότητα. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής (tab) χωρίς κληρονομικότητα. |
| [getTabs()](#getTabs--) | Επιστρέφει τις εσοχές (tabs) μιας παραγράφου. |
| [getFontAlignment()](#getFontAlignment--) | Επιστρέφει ή ορίζει την ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Επιστρέφει ή ορίζει την ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Επιστρέφει την προεπιλεγμένη μορφή τμήματος μιας παραγράφου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με εφαρμοσμένη κληρονομικότητα. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Επιστρέφει τη μορφή κουκίδας της παραγράφου. Μόνο για ανάγνωση [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Επιστρέφει:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Επιστρέφει ή ορίζει το βάθος της παραγράφου. Η τιμή 0 σημαίνει αόριστη τιμή. Ανάγνωση/Εγγραφή short.

**Επιστρέφει:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Επιστρέφει ή ορίζει το βάθος της παραγράφου. Η τιμή 0 σημαίνει αόριστη τιμή. Ανάγνωση/Εγγραφή short.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Επιστρέφει ή ορίζει τη στοίχιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

**Επιστρέφει:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Επιστρέφει ή ορίζει τη στοίχιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. Η θετική τιμή σημαίνει ποσοστό, η αρνητική – μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. Η θετική τιμή σημαίνει ποσοστό, η αρνητική – μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Επιστρέφει ή ορίζει το διάστημα πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Επιστρέφει ή ορίζει το διάστημα πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Επιστρέφει ή ορίζει το διάστημα μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Επιστρέφει ή ορίζει το διάστημα μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Καθορίζει αν η ανακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Καθορίζει αν η ανακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Καθορίζει αν η γραφή από δεξιά προς αριστερά χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Καθορίζει αν η γραφή από δεξιά προς αριστερά χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Καθορίζει αν η λατινική ανακοπή γραμμής χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Καθορίζει αν η λατινική ανακοπή γραμμής χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Επιστρέφει ή ορίζει την πρώτη γραμμή εσοχής/κρεμαστής εσοχής της παραγράφου χωρίς κληρονομικότητα. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Επιστρέφει ή ορίζει την πρώτη γραμμή εσοχής/κρεμαστής εσοχής της παραγράφου χωρίς κληρονομικότητα. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής (tab) χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής (tab) χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Επιστρέφει τις εσοχές (tabs) μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ITabCollection](../../com.aspose.slides/itabcollection).

**Επιστρέφει:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Επιστρέφει ή ορίζει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Επιστρέφει:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Επιστρέφει ή ορίζει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/Εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Επιστρέφει την προεπιλεγμένη μορφή τμήματος μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IPortionFormat](../../com.aspose.slides/iportionformat).

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με εφαρμοσμένη κληρονομικότητα.

**Επιστρέφει:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).