---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά την αναφορά του στυλ σχημάτων.
type: docs
url: /el/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Αναπαριστά την αναφορά του στυλ ενός σχήματος.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLineColor()](#getLineColor--) | Επιστρέφει το χρώμα περιγράμματος ενός σχήματος. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Επιστρέφει ή ορίζει τον δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Επιστρέφει ή ορίζει τον δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. |
| [getFillColor()](#getFillColor--) | Επιστρέφει το χρώμα γεμίσματος ενός σχήματος. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Επιστρέφει ή ορίζει τον δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Επιστρέφει ή ορίζει τον δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. |
| [getEffectColor()](#getEffectColor--) | Επιστρέφει το χρώμα εφέ ενός σχήματος. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Επιστρέφει ή ορίζει τον δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Επιστρέφει ή ορίζει τον δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. |
| [getFontColor()](#getFontColor--) | Επιστρέφει το χρώμα γραμματοσειράς ενός σχήματος. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Επιστρέφει ή ορίζει τον δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Επιστρέφει ή ορίζει τον δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Επιστρέφει το χρώμα περιγράμματος ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Επιστρέφει ή ορίζει τον δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Επιστρέφει ή ορίζει τον δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Επιστρέφει το χρώμα γεμίσματος ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Επιστρέφει ή ορίζει τον δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. 0 σημαίνει χωρίς γέμισμα, θετική τιμή - δείκτης στα στυλ γεμίσματος του θέματος, αρνητική τιμή - δείκτης στα στυλ φόντου του θέματος. Ανάγνωση/εγγραφή short.

**Επιστρέφει:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Επιστρέφει ή ορίζει τον δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. 0 σημαίνει χωρίς γέμισμα, θετική τιμή - δείκτης στα στυλ γεμίσματος του θέματος, αρνητική τιμή - δείκτης στα στυλ φόντου του θέματος. Ανάγνωση/εγγραφή short.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Επιστρέφει το χρώμα εφέ ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Επιστρέφει ή ορίζει τον δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Επιστρέφει ή ορίζει τον δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Επιστρέφει το χρώμα γραμματοσειράς ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Επιστρέφει ή ορίζει τον δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. Ανάγνωση/εγγραφή [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Επιστρέφει:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Επιστρέφει ή ορίζει τον δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. Ανάγνωση/εγγραφή [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |