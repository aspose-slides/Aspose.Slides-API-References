---
title: IFillFormat
second_title: Aspose.Slides για την αναφορά API Java
description: Αναπαριστά επιλογές διαμόρφωσης γεμίσματος.
type: docs
url: /el/com.aspose.slides/ifillformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Αναπαριστά επιλογές διαμόρφωσης γεμίσματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillType()](#getFillType--) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [setFillType(byte value)](#setFillType-byte-) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα γεμίσματος. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή διαβάθμισης γεμίσματος. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή μοτίβου γεμίσματος. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Επιστρέφει τη μορφή εικόνας γεμίσματος. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
| [getEffective()](#getEffective--) | Αποκτά τα αποτελεσματικά δεδομένα διαμόρφωσης γεμίσματος με την εφαρμοσμένη κληρονομικότητα. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Επιστρέφει ή ορίζει τον τύπο γεμίσματος. Ανάγνωση/εγγραφή [FillType](../../com.aspose.slides/filltype).

**Επιστρέφει:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο γεμίσματος. Ανάγνωση/εγγραφή [FillType](../../com.aspose.slides/filltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Επιστρέφει το χρώμα γεμίσματος. Μόνο-ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Επιστρέφει τη μορφή διαβάθμισης γεμίσματος. Μόνο-ανάγνωση [IGradientFormat](../../com.aspose.slides/igradientformat).

**Επιστρέφει:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Επιστρέφει τη μορφή μοτίβου γεμίσματος. Μόνο-ανάγνωση [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Επιστρέφει:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Επιστρέφει τη μορφή εικόνας γεμίσματος. Μόνο-ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Αποκτά τα αποτελεσματικά δεδομένα διαμόρφωσης γεμίσματος με την εφαρμοσμένη κληρονομικότητα.

**Επιστρέφει:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Ένα [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).