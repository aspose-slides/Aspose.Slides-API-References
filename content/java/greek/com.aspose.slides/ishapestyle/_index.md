---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά την αναφορά στυλ των σχημάτων.
type: docs
url: /el/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Αναπαριστά την αναφορά στυλ ενός σχήματος.
## Methods

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Επιστρέφει το χρώμα περιγράμματος ενός σχήματος. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Επιστρέφει ή ορίζει το δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Επιστρέφει ή ορίζει το δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. |
| [getFillColor()](#getFillColor--) | Επιστρέφει το χρώμα γεμίσματος ενός σχήματος. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Επιστρέφει ή ορίζει το δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Επιστρέφει ή ορίζει το δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. |
| [getEffectColor()](#getEffectColor--) | Επιστρέφει το χρώμα εφέ ενός σχήματος. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Επιστρέφει ή ορίζει το δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Επιστρέφει ή ορίζει το δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. |
| [getFontColor()](#getFontColor--) | Επιστρέφει το χρώμα γραμματοσειράς ενός σχήματος. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Επιστρέφει ή ορίζει το δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Επιστρέφει ή ορίζει το δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Επιστρέφει το χρώμα περιγράμματος ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Επιστρέφει ή ορίζει το δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή int.

**Returns:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Επιστρέφει ή ορίζει το δείκτη στήλης της γραμμής σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Επιστρέφει το χρώμα γεμίσματος ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Επιστρέφει ή ορίζει το δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. 0 σημαίνει χωρίς γέμισμα, θετική τιμή – δείκτης στις γεμιστικές επιλογές του θέματος, αρνητική τιμή – δείκτης στις επιλογές φόντου του θέματος. Ανάγνωση/εγγραφή short.

**Returns:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Επιστρέφει ή ορίζει το δείκτη στήλης γεμίσματος του σχήματος σε πλέγματα στυλ. 0 σημαίνει χωρίς γέμισμα, θετική τιμή – δείκτης στις γεμιστικές επιλογές του θέματος, αρνητική τιμή – δείκτης στις επιλογές φόντου του θέματος. Ανάγνωση/εγγραφή short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Επιστρέφει το χρώμα εφέ ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Επιστρέφει ή ορίζει το δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή long.

**Returns:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Επιστρέφει ή ορίζει το δείκτη στήλης εφέ του σχήματος σε ένα πλέγμα στυλ. Ανάγνωση/εγγραφή long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Επιστρέφει το χρώμα γραμματοσειράς ενός σχήματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Επιστρέφει ή ορίζει το δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. Ανάγνωση/εγγραφή [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Returns:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Επιστρέφει ή ορίζει το δείκτη γραμματοσειράς του σχήματος σε μια συλλογή γραμματοσειρών. Ανάγνωση/εγγραφή [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |