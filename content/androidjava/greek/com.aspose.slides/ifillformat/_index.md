---
title: IFillFormat
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει επιλογές μορφοποίησης γεμίσματος.
type: docs
url: /el/com.aspose.slides/ifillformat/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Αντιπροσωπεύει επιλογές μορφοποίησης γεμίσματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillType()](#getFillType--) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [setFillType(byte value)](#setFillType-byte-) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα γεμίσματος. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή γεμίσματος μοτίβου. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Επιστρέφει τη μορφή γεμίσματος εικόνας. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με το σχήμα. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με το σχήμα. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γεμίσματος με την εφαρμογή της κληρονομικότητας. |
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

Επιστρέφει το χρώμα γεμίσματος. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. Μόνο για ανάγνωση [IGradientFormat](../../com.aspose.slides/igradientformat).

**Επιστρέφει:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Επιστρέφει τη μορφή γεμίσματος μοτίβου. Μόνο για ανάγνωση [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Επιστρέφει:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Επιστρέφει τη μορφή γεμίσματος εικόνας. Μόνο για ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γεμίσματος με την εφαρμογή της κληρονομικότητας.

**Επιστρέφει:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).