---
title: IChartParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά τις ιδιότητες μορφοποίησης παραγράφου ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/ichartparagraphformat/
---```
public interface IChartParagraphFormat
```

Αναπαριστά τις ιδιότητες μορφοποίησης παραγράφου ενός διαγράμματος.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getAlignment()](#getAlignment--) | Επιστρέφει ή ορίζει την στοίχιση του κειμένου σε μια παράγραφο. |
| [setAlignment(int value)](#setAlignment-int-) | Επιστρέφει ή ορίζει την στοίχιση του κειμένου σε μια παράγραφο. |
| [getSpaceWithin()](#getSpaceWithin--) | Επιστρέφει ή ορίζει την ποσότητα του χώρου μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Επιστρέφει ή ορίζει την ποσότητα του χώρου μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [getSpaceBefore()](#getSpaceBefore--) | Επιστρέφει ή ορίζει την ποσότητα του χώρου πριν από την πρώτη γραμμή σε μια παράγραφο. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Επιστρέφει ή ορίζει την ποσότητα του χώρου πριν από την πρώτη γραμμή σε μια παράγραφο. |
| [getSpaceAfter()](#getSpaceAfter--) | Επιστρέφει ή ορίζει την ποσότητα του χώρου μετά την τελευταία γραμμή σε μια παράγραφο. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Επιστρέφει ή ορίζει την ποσότητα του χώρου μετά την τελευταία γραμμή σε μια παράγραφο. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Καθορίζει εάν χρησιμοποιείται η ασιατική διάσπαση γραμμής σε μια παράγραφο. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Καθορίζει εάν χρησιμοποιείται η ασιατική διάσπαση γραμμής σε μια παράγραφο. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Καθορίζει εάν χρησιμοποιείται η λατινική διάσπαση γραμμής σε μια παράγραφο. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Καθορίζει εάν χρησιμοποιείται η λατινική διάσπαση γραμμής σε μια παράγραφο. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Καθορίζει εάν χρησιμοποιείται το κρεμαστό σημεία στίξης σε μια παράγραφο. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Καθορίζει εάν χρησιμοποιείται το κρεμαστό σημεία στίξης σε μια παράγραφο. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο. |
| [setMarginRight(float value)](#setMarginRight-float-) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο. |
| [getIndent()](#getIndent--) | Επιστρέφει ή ορίζει την πρώτη γραμμή/το κρεμαστό περιθώριο παραγράφου. |
| [setIndent(float value)](#setIndent-float-) | Επιστρέφει ή ορίζει την πρώτη γραμμή/το κρεμαστό περιθώριο παραγράφου. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος ταμπ. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος ταμπ. |
| [getTabs()](#getTabs--) | Επιστρέφει τα ταμπ της παραγράφου. |
| [getFontAlignment()](#getFontAlignment--) | Επιστρέφει ή ορίζει τη στοίχιση γραμματοσειράς σε μια παράγραφο. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Επιστρέφει ή ορίζει τη στοίχιση γραμματοσειράς σε μια παράγραφο. |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Επιστρέφει ή ορίζει την στοίχιση του κειμένου σε μια παράγραφο. Ανάγνωση/εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

**Επιστρέφει:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Επιστρέφει ή ορίζει την στοίχιση του κειμένου σε μια παράγραφο. Ανάγνωση/εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Επιστρέφει ή ορίζει την ποσότητα του χώρου μεταξύ των βασικών γραμμών σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Επιστρέφει ή ορίζει την ποσότητα του χώρου μεταξύ των βασικών γραμμών σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Επιστρέφει ή ορίζει την ποσότητα του χώρου πριν από την πρώτη γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Επιστρέφει ή ορίζει την ποσότητα του χώρου πριν από την πρώτη γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Επιστρέφει ή ορίζει την ποσότητα του χώρου μετά την τελευταία γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Επιστρέφει ή ορίζει την ποσότητα του χώρου μετά την τελευταία γραμμή σε μια παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Καθορίζει εάν χρησιμοποιείται η ασιατική διάσπαση γραμμής σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Καθορίζει εάν χρησιμοποιείται η ασιατική διάσπαση γραμμής σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Καθορίζει εάν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Καθορίζει εάν χρησιμοποιείται η λατινική διάσπαση γραμμής σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Καθορίζει εάν χρησιμοποιείται η λατινική διάσπαση γραμμής σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Καθορίζει εάν χρησιμοποιείται το κρεμαστό σημεία στίξης σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Καθορίζει εάν χρησιμοποιείται το κρεμαστό σημεία στίξης σε μια παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Επιστρέφει ή ορίζει την πρώτη γραμμή/το κρεμαστό περιθώριο παραγράφου. Το κρεμαστό περιθώριο μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Επιστρέφει ή ορίζει την πρώτη γραμμή/το κρεμαστό περιθώριο παραγράφου. Το κρεμαστό περιθώριο μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος ταμπ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος ταμπ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Επιστρέφει τα ταμπ της παραγράφου. Μόνο ανάγνωση [ITabCollection](../../com.aspose.slides/itabcollection).

**Επιστρέφει:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Επιστρέφει ή ορίζει τη στοίχιση γραμματοσειράς σε μια παράγραφο. Ανάγνωση/εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Επιστρέφει:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Επιστρέφει ή ορίζει τη στοίχιση γραμματοσειράς σε μια παράγραφο. Ανάγνωση/εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |