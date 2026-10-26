---
title: ILineFillFormat
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει τις ιδιότητες για τη γέμιση γραμμών.
type: docs
url: /el/com.aspose.slides/ilinefillformat/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Αντιπροσωπεύει τις ιδιότητες για τη γέμιση γραμμών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillType()](#getFillType--) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [setFillType(byte value)](#setFillType-byte-) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα ενός στερεού γεμίσματος. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή διαβάθμισης γεμίσματος. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή μοτίβου γεμίσματος. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει αν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Καθορίζει αν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
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

Επιστρέφει το χρώμα ενός στερεού γεμίσματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Επιστρέφει τη μορφή διαβάθμισης γεμίσματος. Μόνο ανάγνωση [IGradientFormat](../../com.aspose.slides/igradientformat).

**Επιστρέφει:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Επιστρέφει τη μορφή μοτίβου γεμίσματος. Μόνο ανάγνωση [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Επιστρέφει:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Καθορίζει αν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Καθορίζει αν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |