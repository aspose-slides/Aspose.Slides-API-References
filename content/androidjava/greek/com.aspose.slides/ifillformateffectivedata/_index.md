---
title: IFillFormatEffectiveData
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες διαμόρφωσης γεμίσματος.
type: docs
url: /el/com.aspose.slides/ifillformateffectivedata/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες διαμόρφωσης γεμίσματος.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [IFillFormat](../../com.aspose.slides/ifillformat) για την επιστροφή αποτελεσματικών τιμών διαμόρφωσης με εφαρμοσμένη κληρονομικότητα.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillType()](#getFillType--) | Returns the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Gets the fill color defined by a color scheme. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Επιστρέφει τον τύπο γεμίσματος. Μόνο για ανάγνωση [FillType](../../com.aspose.slides/filltype).

**Επιστρέφει:**
byte

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

Επιστρέφει το χρώμα γεμίσματος. Μόνο για ανάγνωση java.lang.Integer.

**Επιστρέφει:**
java.lang.Integer

### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

Λαμβάνει το χρώμα γεμίσματος που ορίζεται από ένα σχήμα χρωμάτων. Η τιμή [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) υποδεικνύει ότι το SolidFillColor (\#getSolidFillColor.getSolidFillColor) δεν είναι χρώμα σχήματος. Μόνο για ανάγνωση [SchemeColor](../../com.aspose.slides/schemecolor).

**Επιστρέφει:**
int

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

Επιστρέφει τη μορφή γεμίσματος μοτίβου. Μόνο για ανάγνωση [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Επιστρέφει:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

Επιστρέφει τη μορφή γεμίσματος εικόνας. Μόνο για ανάγνωση [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Επιστρέφει:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Καθορίζει αν το γέμισμα πρέπει να περιστραφεί με το σχήμα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean