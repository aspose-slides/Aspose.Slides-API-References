---
title: ILineFillFormat
second_title: Aspose.Slides για την τεκμηρίωση API της Java
description: Αναπαριστά ιδιότητες για τη γέμιση γραμμών.
type: docs
url: /el/com.aspose.slides/ilinefillformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Αναπαριστά ιδιότητες για τη γέμιση γραμμών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillType()](#getFillType--) | Επιστρέφει ή θέτει τον τύπο γέμισης. |
| [setFillType(byte value)](#setFillType-byte-) | Επιστρέφει ή θέτει τον τύπο γέμισης. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα ενός στερεού γέμισης. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή γέμισης διαβάθμισης. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή γέμισης μοτίβου. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με ένα σχήμα. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με ένα σχήμα. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Επιστρέφει ή θέτει τον τύπο γέμισης. Ανάγνωση/εγγραφή [FillType](../../com.aspose.slides/filltype).

**Επιστροφή:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Επιστρέφει ή θέτει τον τύπο γέμισης. Ανάγνωση/εγγραφή [FillType](../../com.aspose.slides/filltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Επιστρέφει το χρώμα ενός στερεού γέμισης. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστροφή:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Επιστρέφει τη μορφή γέμισης διαβάθμισης. Μόνο ανάγνωση [IGradientFormat](../../com.aspose.slides/igradientformat).

**Επιστροφή:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Επιστρέφει τη μορφή γέμισης μοτίβου. Μόνο ανάγνωση [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Επιστροφή:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με ένα σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστροφή:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με ένα σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |