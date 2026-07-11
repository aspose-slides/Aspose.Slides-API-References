---
title: LineFillFormat
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ιδιότητες για τη γέμιση γραμμών.
type: docs
url: /el/com.aspose.slides/linefillformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Αντιπροσωπεύει ιδιότητες για τη γέμιση γραμμών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [setFillType(byte value)](#setFillType-byte-) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα ενός συμπαγούς γεμίσματος. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή διαβαθμισμένου γεμίσματος. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή γεμίσματος με μοτίβο. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Επιστρέφει ή ορίζει τον τύπο γεμίσματος. Ανάγνωση/εγγραφή [FillType](../../com.aspose.slides/filltype).

**Επιστρέφει:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Επιστρέφει ή ορίζει τον τύπο γεμίσματος. Ανάγνωση/εγγραφή [FillType](../../com.aspose.slides/filltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Επιστρέφει το χρώμα ενός συμπαγούς γεμίσματος. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Επιστρέφει τη μορφή διαβαθμισμένου γεμίσματος. Μόνο για ανάγνωση [IGradientFormat](../../com.aspose.slides/igradientformat).

**Επιστρέφει:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Επιστρέφει τη μορφή γεμίσματος με μοτίβο. Μόνο για ανάγνωση [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Επιστρέφει:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)