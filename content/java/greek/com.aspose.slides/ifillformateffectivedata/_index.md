---
title: IFillFormatEffectiveData
second_title: Aspose.Slides για Java API Αναφορά
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες μορφοποίησης γεμίσματος.
type: docs
url: /el/com.aspose.slides/ifillformateffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες μορφοποίησης γεμίσματος.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [IFillFormat](../../com.aspose.slides/ifillformat) για να επιστρέφει αποτελεσματικές τιμές μορφοποίησης με εφαρμογμένη κληρονομικότητα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillType()](#getFillType--) | Επιστρέφει τον τύπο γεμίσματος. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα γεμίσματος. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Λαμβάνει το χρώμα γεμίσματος που ορίζεται από ένα χρωματικό σχήμα. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή γεμίσματος μοτίβου. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Επιστρέφει τη μορφή γεμίσματος εικόνας. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει αν το γέμισμα πρέπει να περιστραφεί μαζί με το σχήμα. |

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

Επιστρέφει το χρώμα γεμίσματος. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color

### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

Λαμβάνει το χρώμα γεμίσματος που ορίζεται από ένα χρωματικό σχήμα. Η τιμή [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) υποδεικνύει ότι το SolidFillColor (\#getSolidFillColor.getSolidFillColor) δεν είναι χρωματικό σχήμα. Μόνο για ανάγνωση [SchemeColor](../../com.aspose.slides/schemecolor).

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

Καθορίζει αν το γέμισμα πρέπει να περιστραφεί μαζί με το σχήμα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean