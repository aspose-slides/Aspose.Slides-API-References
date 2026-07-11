---
title: LineFormat
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τη μορφή μιας γραμμής.
type: docs
url: /el/com.aspose.slides/lineformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Αναπαριστά τη μορφή μιας γραμμής.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Επιστρέφει true εάν η μορφή γραμμής δεν είναι ορισμένη (όπως μόλις δημιουργήθηκε, προεπιλογή). |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τη μορφή γεμίσματος μιας γραμμής. |
| [getSketchFormat()](#getSketchFormat--) | Επιστρέφει τη μορφή σκίτσου μιας γραμμής. |
| [getWidth()](#getWidth--) | Επιστρέφει ή ορίζει το πλάτος μιας γραμμής. |
| [setWidth(double value)](#setWidth-double-) | Επιστρέφει ή ορίζει το πλάτος μιας γραμμής. |
| [getDashStyle()](#getDashStyle--) | Επιστρέφει ή ορίζει το στυλ παύλας της γραμμής. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Επιστρέφει ή ορίζει το στυλ παύλας της γραμμής. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Επιστρέφει ή ορίζει το προσαρμοσμένο μοτίβο παύλας. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Επιστρέφει ή ορίζει το προσαρμοσμένο μοτίβο παύλας. |
| [getCapStyle()](#getCapStyle--) | Επιστρέφει ή ορίζει το στυλ άκρου της γραμμής. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Επιστρέφει ή ορίζει το στυλ άκρου της γραμμής. |
| [getStyle()](#getStyle--) | Επιστρέφει ή ορίζει το στυλ γραμμής. |
| [setStyle(byte value)](#setStyle-byte-) | Επιστρέφει ή ορίζει το στυλ γραμμής. |
| [getAlignment()](#getAlignment--) | Επιστρέφει ή ορίζει την ευθυγράμμιση της γραμμής. |
| [setAlignment(byte value)](#setAlignment-byte-) | Επιστρέφει ή ορίζει την ευθυγράμμιση της γραμμής. |
| [getJoinStyle()](#getJoinStyle--) | Επιστρέφει ή ορίζει το στυλ ένωσης των γραμμών. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Επιστρέφει ή ορίζει το στυλ ένωσης των γραμμών. |
| [getMiterLimit()](#getMiterLimit--) | Επιστρέφει ή ορίζει το όριο μύτης μιας γραμμής. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Επιστρέφει ή ορίζει το όριο μύτης μιας γραμμής. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στην αρχή μιας γραμμής. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στο τέλος μιας γραμμής. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στο τέλος μιας γραμμής. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στην αρχή μιας γραμμής. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στο τέλος μιας γραμμής. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στο τέλος μιας γραμμής. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στην αρχή μιας γραμμής. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στο τέλος μιας γραμμής. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στο τέλος μιας γραμμής. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Καθορίζει εάν τα δύο αντικείμενα LineFormat είναι ίσα. |
| [getEffective()](#getEffective--) | Λαμβάνει αποτελεσματικά δεδομένα μορφοποίησης γραμμής με την κληρονομικότητα εφαρμόσιμη. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο ανάγνωση long.

**Επιστρέφει:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Συγκρίνει με το καθορισμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Επιστρέφει:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```


Επιστρέφει true εάν η μορφή γραμμής δεν είναι ορισμένη (όπως μόλις δημιουργήθηκε, προεπιλογή). Μόνο ανάγνωση boolean .

**Επιστρέφει:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```


Επιστρέφει τη μορφή γεμίσματος μιας γραμμής. Μόνο ανάγνωση [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Επιστρέφει:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```


Επιστρέφει τη μορφή σκίτσου μιας γραμμής. Μόνο ανάγνωση [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Επιστρέφει:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Επιστρέφει ή ορίζει το πλάτος μιας γραμμής. Ανάγνωση/Εγγραφή double .

**Επιστρέφει:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Επιστρέφει ή ορίζει το πλάτος μιας γραμμής. Ανάγνωση/Εγγραφή double .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```


Επιστρέφει ή ορίζει το στυλ παύλας της γραμμής. Ανάγνωση/Εγγραφή [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Επιστρέφει:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```


Επιστρέφει ή ορίζει το στυλ παύλας της γραμμής. Ανάγνωση/Εγγραφή [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```


Επιστρέφει ή ορίζει το προσαρμοσμένο μοτίβο παύλας. Ανάγνωση/Εγγραφή float[] .

**Επιστρέφει:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```


Επιστρέφει ή ορίζει το προσαρμοσμένο μοτίβο παύλας. Ανάγνωση/Εγγραφή float[] .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```


Επιστρέφει ή ορίζει το στυλ άκρου της γραμμής. Ανάγνωση/Εγγραφή [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Επιστρέφει:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```


Επιστρέφει ή ορίζει το στυλ άκρου της γραμμής. Ανάγνωση/Εγγραφή [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```


Επιστρέφει ή ορίζει το στυλ γραμμής. Ανάγνωση/Εγγραφή [LineStyle](../../com.aspose.slides/linestyle).

**Επιστρέφει:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```


Επιστρέφει ή ορίζει το στυλ γραμμής. Ανάγνωση/Εγγραφή [LineStyle](../../com.aspose.slides/linestyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```


Επιστρέφει ή ορίζει την ευθυγράμμιση της γραμμής. Ανάγνωση/Εγγραφή [LineAlignment](../../com.aspose.slides/linealignment).

**Επιστρέφει:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```


Επιστρέφει ή ορίζει την ευθυγράμμιση της γραμμής. Ανάγνωση/Εγγραφή [LineAlignment](../../com.aspose.slides/linealignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```


Επιστρέφει ή ορίζει το στυλ ένωσης των γραμμών. Ανάγνωση/Εγγραφή [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Επιστρέφει:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```


Επιστρέφει ή ορίζει το στυλ ένωσης των γραμμών. Ανάγνωση/Εγγραφή [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Επιστρέφει ή ορίζει το όριο μύτης μιας γραμμής. Ανάγνωση/Εγγραφή float .

**Επιστρέφει:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Επιστρέφει ή ορίζει το όριο μύτης μιας γραμμής. Ανάγνωση/Εγγραφή float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```


Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Επιστρέφει:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```


Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```


Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Επιστρέφει:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```


Επιστρέφει ή ορίζει το στυλ κεφαλής βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```


Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Επιστρέφει:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```


Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```


Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Επιστρέφει:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```


Επιστρέφει ή ορίζει το πλάτος κεφαλής βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```


Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Επιστρέφει:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```


Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```


Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Επιστρέφει:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```


Επιστρέφει ή ορίζει το μήκος κεφαλής βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```


Καθορίζει εάν τα δύο αντικείμενα LineFormat είναι ίσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Η LineFormat για σύγκριση με την τρέχουσα LineFormat. |

**Επιστρέφει:**
boolean - **true** εάν το καθορισμένο LineFormat είναι ίσο με το τρέχον LineFormat· διαφορετικά **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```


Λαμβάνει αποτελεσματικά δεδομένα μορφοποίησης γραμμής με την κληρονομικότητα εφαρμόσιμη.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).