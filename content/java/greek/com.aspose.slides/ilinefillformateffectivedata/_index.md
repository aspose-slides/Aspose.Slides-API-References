---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides για Java API Αναφορά
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες γεμίσματος γραμμής.
type: docs
url: /el/com.aspose.slides/ilinefillformateffectivedata/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες γεμίσματος γραμμής.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillType()](#getFillType--) | Επιστρέφει τον τύπο γεμίσματος. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα ενός συμπαγούς γεμίσματος. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή γεμίσματος προτύπου. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει εάν το γέμισμα πρέπει να περιστραφεί με ένα σχήμα. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Επιστρέφει τον τύπο γεμίσματος. Μόνο για ανάγνωση [FillType](../../com.aspose.slides/filltype).

**Επιστρέφει:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Επιστρέφει το χρώμα ενός συμπαγούς γεμίσματος. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. Μόνο για ανάγνωση [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Επιστρέφει:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Επιστρέφει τη μορφή γεμίσματος προτύπου. Μόνο για ανάγνωση [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Επιστρέφει:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Καθορίζει εάν το γέμισμα πρέπει να περιστραφεί με ένα σχήμα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean