---
title: IChartParagraphFormat
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά τις ιδιότητες μορφοποίησης παραγράφου ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/ichartparagraphformat/
---```
public interface IChartParagraphFormat
```

Αναπαριστά τις ιδιότητες μορφοποίησης παραγράφου ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAlignment()](#getAlignment--) | Επιστρέφει ή ορίζει τη στοίχιση του κειμένου σε μια παράγραφο. |
| [setAlignment(int value)](#setAlignment-int-) | Επιστρέφει ή ορίζει τη στοίχιση του κειμένου σε μια παράγραφο. |
| [getSpaceWithin()](#getSpaceWithin--) | Επιστρέφει ή ορίζει το ποσό του κενού μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Επιστρέφει ή ορίζει το ποσό του κενού μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [getSpaceBefore()](#getSpaceBefore--) | Επιστρέφει ή ορίζει το ποσό του κενού πριν από την πρώτη γραμμή σε μια παράγραφο. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Επιστρέφει ή ορίζει το ποσό του κενού πριν από την πρώτη γραμμή σε μια παράγραφο. |
| [getSpaceAfter()](#getSpaceAfter--) | Επιστρέφει ή ορίζει το ποσό του κενού μετά την τελευταία γραμμή σε μια παράγραφο. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Επιστρέφει ή ορίζει το ποσό του κενού μετά την τελευταία γραμμή σε μια παράγραφο. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Καθορίζει αν η διακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Καθορίζει αν η διακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει αν η γραφή Δεξιά προς Αριστερά χρησιμοποιείται σε μια παράγραφο. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Καθορίζει αν η γραφή Δεξιά προς Αριστερά χρησιμοποιείται σε μια παράγραφο. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Καθορίζει αν η διακοπή γραμμής Λατινικού χρησιμοποιείται σε μια παράγραφο. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Καθορίζει αν η διακοπή γραμμής Λατινικού χρησιμοποιείται σε μια παράγραφο. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο. |
| [setMarginRight(float value)](#setMarginRight-float-) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο. |
| [getIndent()](#getIndent--) | Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. |
| [setIndent(float value)](#setIndent-float-) | Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής. |
| [getTabs()](#getTabs--) | Επιστρέφει τις εσοχές μιας παραγράφου. |
| [getFontAlignment()](#getFontAlignment--) | Επιστρέφει ή ορίζει την στοίχιση γραμματοσειράς σε μια παράγραφο. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Επιστρέφει ή ορίζει την στοίχιση γραμματοσειράς σε μια παράγραφο. |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Επιστρέφει ή ορίζει τη στοίχιση του κειμένου σε μια παράγραφο. Ανάγνωση/εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

**Επιστρέφει:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```


Επιστρέφει ή ορίζει τη στοίχιση του κειμένου σε μια παράγραφο. Ανάγνωση/εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Επιστρέφει ή ορίζει το ποσό του κενού μεταξύ των βασικών γραμμών σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```


Επιστρέφει ή ορίζει το ποσό του κενού μεταξύ των βασικών γραμμών σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Επιστρέφει ή ορίζει το ποσό του κενού πριν από την πρώτη γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```


Επιστρέφει ή ορίζει το ποσό του κενού πριν από την πρώτη γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Επιστρέφει ή ορίζει το ποσό του κενού μετά την τελευταία γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```


Επιστρέφει ή ορίζει το ποσό του κενού μετά την τελευταία γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```


Καθορίζει αν η διακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```


Καθορίζει αν η διακοπή γραμμής Ανατολικής Ασίας χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```


Καθορίζει αν η γραφή Δεξιά προς Αριστερά χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```


Καθορίζει αν η γραφή Δεξιά προς Αριστερά χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```


Καθορίζει αν η διακοπή γραμμής Λατινικού χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```


Καθορίζει αν η διακοπή γραμμής Λατινικού χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```


Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```


Καθορίζει αν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```


Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```


Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```


Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```


Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```


Επιστρέφει τις εσοχές μιας παραγράφου. Μόνο ανάγνωση [ITabCollection](../../com.aspose.slides/itabcollection).

**Επιστρέφει:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Επιστρέφει ή ορίζει την στοίχιση γραμματοσειράς σε μια παράγραφο. Ανάγνωση/εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Επιστρέφει:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```


Επιστρέφει ή ορίζει την στοίχιση γραμματοσειράς σε μια παράγραφο. Ανάγνωση/εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |