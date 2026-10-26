---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες γεμίσματος γραμμής.
type: docs
url: /el/com.aspose.slides/ilinefillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες γεμίσματος γραμμής.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Επιστρέφει τον τύπο γεμίσματος. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα ενός συμπαγούς γεμίσματος. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή γεμίσματος προτύπου. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει αν το γεμάσμα πρέπει να περιστρέφεται μαζί με το σχήμα. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Επιστρέφει τον τύπο γεμίσματος. Μόνο για ανάγνωση [FillType](../../com.aspose.slides/filltype).

**Returns:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Επιστρέφει το χρώμα ενός συμπαγούς γεμίσματος. Μόνο για ανάγνωση java.lang.Integer.

**Returns:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. Μόνο για ανάγνωση [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Returns:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Επιστρέφει τη μορφή γεμίσματος προτύπου. Μόνο για ανάγνωση [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Returns:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Καθορίζει αν το γεμάσμα πρέπει να περιστρέφεται μαζί με το σχήμα. Μόνο για ανάγνωση boolean.

**Returns:**
boolean