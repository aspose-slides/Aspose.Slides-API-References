---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες μορφοποίησης παραγράφου.
type: docs
url: /el/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες μορφοποίησης παραγράφου.

--------------------

This interface is used together with the [IParagraphFormat](../../com.aspose.slides/iparagraphformat) interface to return effective formatting values with inheritance applied.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBullet()](#getBullet--) | Επιστρέφει τη μορφή κουκκίδας μιας παραγράφου. |
| [getDepth()](#getDepth--) | Επιστρέφει το βάθος μιας παραγράφου. |
| [getAlignment()](#getAlignment--) | Επιστρέφει την ευθυγράμμιση του κειμένου σε μια παράγραφο. |
| [getSpaceWithin()](#getSpaceWithin--) | Επιστρέφει το διάστημα μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [getSpaceBefore()](#getSpaceBefore--) | Επιστρέφει το διάστημα πριν από την πρώτη γραμμή σε μια παράγραφο. |
| [getSpaceAfter()](#getSpaceAfter--) | Επιστρέφει το διάστημα μετά την τελευταία γραμμή σε μια παράγραφο. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Καθορίζει εάν χρησιμοποιείται η αλλαγή γραμμής Ανατολικής Ασίας σε μια παράγραφο. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Καθορίζει εάν χρησιμοποιείται η αλλαγή γραμμής Λατινικού σε μια παράγραφο. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Καθορίζει εάν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει το αριστερό περιθώριο σε μια παράγραφο. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει το δεξιό περιθώριο σε μια παράγραφο. |
| [getIndent()](#getIndent--) | Επιστρέφει την εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Επιστρέφει το προεπιλεγμένο μέγεθος εσοχής. |
| [getTabs()](#getTabs--) | Επιστρέφει τις εσοχές μιας παραγράφου. |
| [getFontAlignment()](#getFontAlignment--) | Επιστρέφει την ευθυγράμμιση γραμματοσειράς σε μια παράγραφο. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Επιστρέφει τη προεπιλεγμένη μορφή τμήματος μιας παραγράφου. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Επιστρέφει τη μορφή κουκκίδας μιας παραγράφου. Μόνο για ανάγνωση [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Επιστρέφει:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Επιστρέφει το βάθος μιας παραγράφου. Μόνο για ανάγνωση short.

**Επιστρέφει:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Επιστρέφει την ευθυγράμμιση του κειμένου σε μια παράγραφο. Μόνο για ανάγνωση [TextAlignment](../../com.aspose.slides/textalignment).

**Επιστρέφει:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Επιστρέφει το διάστημα μεταξύ των βασικών γραμμών σε μια παράγραφο. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Επιστρέφει το διάστημα πριν από την πρώτη γραμμή σε μια παράγραφο. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Επιστρέφει το διάστημα μετά την τελευταία γραμμή σε μια παράγραφο. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Καθορίζει εάν χρησιμοποιείται η αλλαγή γραμμής Ανατολικής Ασίας σε μια παράγραφο. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. Μόνο για ανάγνωση boolean.

**Επισ Returns:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Καθορίζει εάν χρησιμοποιείται η αλλαγή γραμμής Λατινικού σε μια παράγραφο. Μόνο για ανάγνωση boolean.

**Επισ Returns:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Καθορίζει εάν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. Μόνο για ανάγνωση boolean.

**Επισ Returns:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Επισ Returns: το αριστερό περιθώριο σε μια παράγραφο. Μόνο για ανάγνωση float.

**Επισ Returns:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Επισ Returns: το δεξιό περιθώριο σε μια παράγραφο. Μόνο για ανάγνωση float.

**Επισ Returns:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Επισ Returns: την εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Μόνο για ανάγνωση float.

**Επισ Returns:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Επισ Returns: το προεπιλεγμένο μέγεθος εσοχής. Μόνο για ανάγνωση float.

**Επισ Returns:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Επισ Returns: τις εσοχές μιας παραγράφου. Μόνο για ανάγνωση ITabEffectiveData[].

**Επισ Returns:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Επισ Returns: την ευθυγράμμιση γραμματοσειράς σε μια παράγραφο. Μόνο για ανάγνωση [FontAlignment](../../com.aspose.slides/fontalignment).

**Επισ Returns:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Επισ Returns: τη προεπιλεγμένη μορφή τμήματος της παραγράφου. Μόνο για ανάγνωση [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Επισ Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)