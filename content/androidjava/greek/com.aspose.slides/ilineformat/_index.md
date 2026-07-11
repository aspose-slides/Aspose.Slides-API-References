---
title: ILineFormat
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τη μορφή μιας γραμμής.
type: docs
url: /el/com.aspose.slides/ilineformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Αναπαριστά τη μορφή μιας γραμμής.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Επιστρέφει true εάν η μορφή της γραμμής δεν έχει οριστεί (όπως μόλις δημιουργήθηκε, προεπιλογή). |
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
| [getJoinStyle()](#getJoinStyle--) | Επιστρέφει ή ορίζει το στυλ σύνδεσης των γραμμών. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Επιστρέφει ή ορίζει το στυλ σύνδεσης των γραμμών. |
| [getMiterLimit()](#getMiterLimit--) | Επιστρέφει ή ορίζει το όριο μιτέρ μιας γραμμής. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Επιστρέφει ή ορίζει το όριο μιτέρ μιας γραμμής. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Επιστρέφει ή ορίζει το στυλ άκρου βέλους στην αρχή μιας γραμμής. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Επιστρέφει ή ορίζει το στυλ άκρου βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Επιστρέφει ή ορίζει το στυλ άκρου βέλους στο τέλος μιας γραμμής. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Επιστρέφει ή ορίζει το στυλ άκρου βέλους στο τέλος μιας γραμμής. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στην αρχή μιας γραμμής. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στο τέλος μιας γραμμής. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στο τέλος μιας γραμμής. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Επιστρέφει ή ορίζει το μήκος άκρου βέλους στην αρχή μιας γραμμής. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Επιστρέφει ή ορίζει το μήκος άκρου βέλους στην αρχή μιας γραμμής. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Επιστρέφει ή ορίζει το μήκος άκρου βέλους στο τέλος μιας γραμμής. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Επιστρέφει ή ορίζει το μήκος άκρου βέλους στο τέλος μιας γραμμής. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Καθορίζει εάν τα δύο παραδείγματα LineFormat είναι ίσα. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γραμμής με την κληρονομικότητα εφαρμοσμένη. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Επιστρέφει true εάν η μορφή της γραμμής δεν έχει οριστεί (όπως μόλις δημιουργήθηκε, προεπιλογή). Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Επιστρέφει τη μορφή γεμίσματος μιας γραμμής. Μόνο ανάγνωση [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Επιστρέφει:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Επιστρέφει τη μορφή σκίτσου μιας γραμμής. Μόνο ανάγνωση [ISketchFormat](../../com.aspose.slides/isketchformat).

**Επιστρέφει:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Επιστρέφει ή ορίζει το πλάτος μιας γραμμής. Ανάγνωση/Εγγραφή double.

**Επιστρέφει:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Επιστρέφει ή ορίζει το πλάτος μιας γραμμής. Ανάγνωση/Εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Επιστρέφει ή ορίζει το στυλ παύλας της γραμμής. Ανάγνωση/Εγγραφή [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Επιστρέφει:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ παύλας της γραμμής. Ανάγνωση/Εγγραφή [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Επιστρέφει ή ορίζει το προσαρμοσμένο μοτίβο παύλας. Ανάγνωση/Εγγραφή float[].

**Επιστρέφει:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Επιστρέφει ή ορίζει το προσαρμοσμένο μοτίβο παύλας. Ανάγνωση/Εγγραφή float[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Επιστρέφει ή ορίζει το στυλ άκρου της γραμμής. Ανάγνωση/Εγγραφή [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Επιστρέφει:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ άκρου της γραμμής. Ανάγνωση/Εγγραφή [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Επιστρέφει ή ορίζει το στυλ γραμμής. Ανάγνωση/Εγγραφή [LineStyle](../../com.aspose.slides/linestyle).

**Επιστρέφει:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ γραμμής. Ανάγνωση/Εγγραφή [LineStyle](../../com.aspose.slides/linestyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Επιστρέφει ή ορίζει την ευθυγράμμιση της γραμμής. Ανάγνωση/Εγγραφή [LineAlignment](../../com.aspose.slides/linealignment).

**Επιστρέφει:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Επιστρέφει ή ορίζει την ευθυγράμμιση της γραμμής. Ανάγνωση/Εγγραφή [LineAlignment](../../com.aspose.slides/linealignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Επιστρέφει ή ορίζει το στυλ σύνδεσης των γραμμών. Ανάγνωση/Εγγραφή [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Επιστρέφει:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ σύνδεσης των γραμμών. Ανάγνωση/Εγγραφή [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Επιστρέφει ή ορίζει το όριο μιτέρ μιας γραμμής. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Επιστρέφει ή ορίζει το όριο μιτέρ μιας γραμμής. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Επιστρέφει ή ορίζει το στυλ άκρου βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Επιστρέφει:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ άκρου βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Επιστρέφει ή ορίζει το στυλ άκρου βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Επιστρέφει:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ άκρου βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Επιστρέφει:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Επιστρέφει:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Επιστρέφει ή ορίζει το πλάτος άκρου βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Επιστρέφει ή ορίζει το μήκος άκρου βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Επιστρέφει:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Επιστρέφει ή ορίζει το μήκος άκρου βέλους στην αρχή μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Επιστρέφει ή ορίζει το μήκος άκρου βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Επιστρέφει:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Επιστρέφει ή ορίζει το μήκος άκρου βέλους στο τέλος μιας γραμμής. Ανάγνωση/Εγγραφή [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Καθορίζει εάν τα δύο παραδείγματα LineFormat είναι ίσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Το LineFormat προς σύγκριση με το τρέχον LineFormat. |

**Επιστρέφει:**
boolean - **true** εάν το συγκεκριμένο LineFormat είναι ίσο με το τρέχον LineFormat· διαφορετικά, **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γραμμής με την κληρονομικότητα εφαρμοσμένη.

**Επιστρέφει:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).