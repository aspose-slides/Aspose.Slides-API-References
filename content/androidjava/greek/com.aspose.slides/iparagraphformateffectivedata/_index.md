---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης παραγράφου.
type: docs
url: /el/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης παραγράφου.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [IParagraphFormat](../../com.aspose.slides/iparagraphformat) για την επιστροφή αποτελεσματικών τιμών μορφοποίησης με εφαρμογή κληρονομικότητας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBullet()](#getBullet--) | Επιστρέφει μια μορφή κουκκίδας μιας παραγράφου. |
| [getDepth()](#getDepth--) | Επιστρέφει το βάθος μιας παραγράφου. |
| [getAlignment()](#getAlignment--) | Επιστρέφει την ευθυγράμμιση κειμένου σε μια παράγραφο. |
| [getSpaceWithin()](#getSpaceWithin--) | Επιστρέφει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [getSpaceBefore()](#getSpaceBefore--) | Επιστρέφει την ποσότητα του διαστήματος πριν από την πρώτη γραμμή σε μια παράγραφο. |
| [getSpaceAfter()](#getSpaceAfter--) | Επιστρέφει την ποσότητα του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Καθορίζει εάν χρησιμοποιείται η διάσπαση γραμμής Ανατολικής Ασίας σε μια παράγραφο. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Καθορίζει εάν χρησιμοποιείται η διάσπαση γραμμής Λατινική σε μια παράγραφο. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Καθορίζει εάν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει το αριστερό περιθώριο σε μια παράγραφο. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει το δεξιό περιθώριο σε μια παράγραφο. |
| [getIndent()](#getIndent--) | Επιστρέφει την εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Επιστρέφει το προεπιλεγμένο μέγεθος ταμπέλας. |
| [getTabs()](#getTabs--) | Επιστρέφει τις ταμπέλες μιας παραγράφου. |
| [getFontAlignment()](#getFontAlignment--) | Επιστρέφει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Επιστρέφει την προεπιλεγμένη μορφή τμήματος της παραγράφου. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Επιστρέφει μια μορφή κουκκίδας μιας παραγράφου. Μόνο ανάγνωση [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Επιστρέφει:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Επιστρέφει το βάθος μιας παραγράφου. Μόνο ανάγνωση short.

**Επιστρέφει:**
short

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Επιστρέφει την ευθυγράμμιση κειμένου σε μια παράγραφο. Μόνο ανάγνωση [TextAlignment](../../com.aspose.slides/textalignment).

**Επιστρέφει:**
int

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Επιστρέφει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. Μόνο ανάγνωση float.

**Επιστρέφει:**
float

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Επιστρέφει την ποσότητα του διαστήματος πριν από την πρώτη γραμμή σε μια παράγραφο. Μόνο ανάγνωση float.

**Επιστρέφει:**
float

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Επιστρέφει την ποσότητα του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο. Μόνο ανάγνωση float.

**Επιστρέφει:**
float

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Καθορίζει εάν χρησιμοποιείται η διάσπαση γραμμής Ανατολικής Ασίας σε μια παράγραφο. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Καθορίζει εάν χρησιμοποιείται η διάσπαση γραμμής Λατινική σε μια παράγραφο. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Καθορίζει εάν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Επιστρέφει το αριστερό περιθώριο σε μια παράγραφο. Μόνο ανάγνωση float.

**Επιστρέφει:**
float

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Επιστρέφει το δεξιό περιθώριο σε μια παράγραφο. Μόνο ανάγνωση float.

**Επιστρέφει:**
float

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Επιστρέφει την εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Μόνο ανάγνωση float.

**Επιστρέφει:**
float

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Επιστρέφει το προεπιλεγμένο μέγεθος ταμπέλας. Μόνο ανάγνωση float.

**Επιστρέφει:**
float

### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Επιστρέφει τις ταμπέλες μιας παραγράφου. Μόνο ανάγνωση ITabEffectiveData[].

**Επιστρέφει:**
com.aspose.slides.ITabEffectiveData[]

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Επιστρέφει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο. Μόνο ανάγνωση [FontAlignment](../../com.aspose.slides/fontalignment).

**Επιστρέφει:**
int

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Επιστρέφει την προεπιλεγμένη μορφή τμήματος της παραγράφου. Μόνο ανάγνωση [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Επιστρέφει:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)