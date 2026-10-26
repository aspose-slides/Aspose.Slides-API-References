---
title: ILineFormatEffectiveData
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες μορφοποίησης γραμμής.
type: docs
url: /el/com.aspose.slides/ilineformateffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες μορφοποίησης γραμμής.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [ILineFormat](../../com.aspose.slides/ilineformat) για να επιστρέφει αποτελεσματικές τιμές μορφοποίησης με εφαρμοσμένη κληρονομικότητα.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τη μορφή γεμίσματος μιας γραμμής. |
| [getSketchFormat()](#getSketchFormat--) | Επιστρέφει τη μορφή σκίτσου μιας γραμμής. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος μιας γραμμής. |
| [getDashStyle()](#getDashStyle--) | Επιστρέφει το στυλ παύλας της γραμμής. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Επιστρέφει το προσαρμοσμένο μοτίβο παύλας. |
| [getCapStyle()](#getCapStyle--) | Επιστρέφει το στυλ άκρου της γραμμής. |
| [getStyle()](#getStyle--) | Επιστρέφει το στυλ της γραμμής. |
| [getAlignment()](#getAlignment--) | Επιστρέφει την ευθυγράμμιση της γραμμής. |
| [getJoinStyle()](#getJoinStyle--) | Επιστρέφει το στυλ σύζευξης γραμμών. |
| [getMiterLimit()](#getMiterLimit--) | Επιστρέφει το όριο μύτης (miter) μιας γραμμής. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Επιστρέφει το στυλ κεφαλής βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Επιστρέφει το στυλ κεφαλής βέλους στο τέλος μιας γραμμής. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Επιστρέφει το πλάτος κεφαλής βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Επιστρέφει το πλάτος κεφαλής βέλους στο τέλος μιας γραμμής. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Επιστρέφει το μήκος κεφαλής βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Επιστρέφει το μήκος κεφαλής βέλους στο τέλος μιας γραμμής. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Καθορίζει αν τα δύο στιγμιότυπα ILineFormatEffectiveData είναι ίσα. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Επιστρέφει τη μορφή γεμίσματος μιας γραμμής. Μόνο για ανάγνωση [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Επιστρέφει:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Επιστρέφει τη μορφή σκίτσου μιας γραμμής. Μόνο για ανάγνωση [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Επιστρέφει:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Επιστρέφει το πλάτος μιας γραμμής. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Επιστρέφει το στυλ παύλας της γραμμής. Μόνο για ανάγνωση [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Επιστρέφει:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Επιστρέφει το προσαρμοσμένο μοτίβο παύλας. Μόνο για ανάγνωση float[].

**Επιστρέφει:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Επιστρέφει το στυλ άκρου της γραμμής. Μόνο για ανάγνωση [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Επιστρέφει:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Επιστρέφει το στυλ της γραμμής. Μόνο για ανάγνωση [LineStyle](../../com.aspose.slides/linestyle).

**Επιστρέφει:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Επιστρέφει την ευθυγράμμιση της γραμμής. Μόνο για ανάγνωση [LineAlignment](../../com.aspose.slides/linealignment).

**Επιστρέφει:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Επιστρέφει το στυλ σύζευξης γραμμών. Μόνο για ανάγνωση [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Επιστρέφει:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Επιστρέφει το όριο μύτης (miter) μιας γραμμής. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Επιστρέφει το στυλ κεφαλής βέλους στην αρχή μιας γραμμής. Μόνο για ανάγνωση [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Επιστρέφει:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Επιστρέφει το στυλ κεφαλής βέλους στο τέλος μιας γραμμής. Μόνο για ανάγνωση [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Επιστρέφει:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Επιστρέφει το πλάτος κεφαλής βέλους στην αρχή μιας γραμμής. Μόνο για ανάγνωση [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Επιστρέφει:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Επιστρέφει το πλάτος κεφαλής βέλους στο τέλος μιας γραμμής. Μόνο για ανάγνωση [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Επιστρέφει:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Επιστρέφει το μήκος κεφαλής βέλους στην αρχή μιας γραμμής. Μόνο για ανάγνωση [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Επιστρέφει:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Επιστρέφει το μήκος κεφαλής βέλους στο τέλος μιας γραμμής. Μόνο για ανάγνωση [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Επιστρέφει:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Καθορίζει αν τα δύο στιγμιότυπα ILineFormatEffectiveData είναι ίσα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | Το ILineFormatEffectiveData για σύγκριση με το τρέχον ILineFormatEffectiveData. |

**Επιστρέφει:**
boolean - **true** εάν το καθορισμένο ILineFormatEffectiveData είναι ίσο με το τρέχον ILineFormatEffectiveData· διαφορετικά, **false**.