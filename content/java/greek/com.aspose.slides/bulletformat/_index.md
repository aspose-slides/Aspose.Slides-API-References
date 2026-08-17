---
title: BulletFormat
second_title: Aspose.Slides για την Java API Αναφορά
description: Αντιπροσωπεύει τις ιδιότητες μορφοποίησης κουκίδων παραγράφου.
type: docs
url: /el/com.aspose.slides/bulletformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Αναπαριστά τις ιδιότητες μορφοποίησης κουκίδων παραγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setType(byte value)](#setType-byte-) | Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getChar()](#getChar--) | Επιστρέφει ή ορίζει τον χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setChar(char value)](#setChar-char-) | Επιστρέφει ή ορίζει τον χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getFont()](#getFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getHeight()](#getHeight--) | Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setHeight(float value)](#setHeight-float-) | Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getColor()](#getColor--) | Επιστρέφει τη μορφή χρώματος μιας κουκίδας παραγράφου χωρίς κληρονομικότητα. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. |
| [isBulletHardColor()](#isBulletHardColor--) | Καθορίζει αν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Καθορίζει αν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [isBulletHardFont()](#isBulletHardFont--) | Καθορίζει αν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Καθορίζει αν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονομικότητα. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ορίζει τις προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν οι κουκίδες είναι ενεργοποιημένες (όπως κάνει το PowerPoint όταν ενεργοποιεί τις κουκίδες/αρίθμηση παραγράφου). |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την εφαρμοσμένη κληρονομικότητα. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή [BulletType](../../com.aspose.slides/bullettype).**

**Επιστρέφει:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή [BulletType](../../com.aspose.slides/bullettype).**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

Επιστρέφει ή ορίζει τον χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή  char .**

**Επιστρέφει:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Επιστρέφει ή ορίζει τον χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή  char .**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).**

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή Float.NaN υποδεικνύει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. **Ανάγνωση/εγγραφή  float .**

--------------------

Μια αρνητική τιμή ύψους σημαίνει ότι το ύψος δίνεται σε σημεία και μια θετική τιμή σημαίνει ότι το ύψος είναι ποσοστό του γύρω κειμένου.

**Επιστρέφει:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή Float.NaN υποδεικνύει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. **Ανάγνωση/εγγραφή  float .**

--------------------

Μια αρνητική τιμή ύψους σημαίνει ότι το ύψος δίνεται σε σημεία και μια θετική τιμή σημαίνει ότι το ύψος είναι ποσοστό του γύρω κειμένου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Επιστρέφει τη μορφή χρώματος μιας κουκίδας παραγράφου χωρίς κληρονομικότητα. **Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).**

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή  short .**

**Επιστρέφει:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή  short .**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).**

**Επιστρέφει:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. **Ανάγνωση/εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Καθορίζει αν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** αν η κουκίδα έχει δικό της χρώμα και **NullableBool.False** αν κληρονομεί χρώμα από το πρώτο τμήμα στην παράγραφο. **Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).**

**Επιστρέφει:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Καθορίζει αν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** αν η κουκίδα έχει δικό της χρώμα και **NullableBool.False** αν κληρονομεί χρώμα από το πρώτο τμήμα στην παράγραφο. **Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Καθορίζει αν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** αν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool.False** αν κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. **Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).**

**Επιστρέφει:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Καθορίζει αν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** αν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool.False** αν κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. **Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).**

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονομικότητα. **Μόνο για ανάγνωση [ISlidesPicture](../../com.aspose.slides/islidespicture).**

**Επιστρέφει:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Ορίζει τις προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν οι κουκίδες είναι ενεργοποιημένες (όπως κάνει το PowerPoint όταν ενεργοποιεί τις κουκίδες/αρίθμηση παραγράφου). Αν οι κουκίδες είναι απενεργοποιημένες, τότε απλώς επαναφέρει το Indent και το MarginLeft της παραγράφου (όπως κάνει το PowerPoint όταν απενεργοποιεί τις κουκίδες/αρίθμηση παραγράφου). Οι μετατοπίσεις εσοχών εφαρμόζονται σε σχέση με το τρέχον context της κουκίδας — IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (καθιστώντας τις τιμές τοπικές).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την εφαρμοσμένη κληρονομικότητα.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. **Μόνο για ανάγνωση long.**

**Επιστρέφει:**
long