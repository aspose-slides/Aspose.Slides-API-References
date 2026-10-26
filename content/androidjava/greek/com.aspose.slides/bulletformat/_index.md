---
title: BulletFormat
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τις ιδιότητες μορφοποίησης κουκίδων παραγράφου.
type: docs
url: /el/com.aspose.slides/bulletformat/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Αναπαριστά ιδιότητες μορφοποίησης κουκίδων παραγράφου.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [setType(byte value)](#setType-byte-) | Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [getChar()](#getChar--) | Επιστρέφει ή ορίζει το χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [setChar(char value)](#setChar-char-) | Επιστρέφει ή ορίζει το χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [getFont()](#getFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [getHeight()](#getHeight--) | Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [setHeight(float value)](#setHeight-float-) | Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [getColor()](#getColor--) | Επιστρέφει τη μορφή χρώματος μιας κουκίδας μιας παραγράφου χωρίς κληρονόμηση. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. |
| [isBulletHardColor()](#isBulletHardColor--) | Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [isBulletHardFont()](#isBulletHardFont--) | Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονόμηση. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ορίζει τις προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Εσοχή παραγράφου και το αριστερό περιθώριο όταν οι κουκίδες είναι ενεργοποιημένες (όπως κάνει το PowerPoint όταν ενεργοποιούνται οι κουκίδες/αρίθμηση παραγράφου). |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την εφαρμοσμένη κληρονόμηση. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [BulletType](../../com.aspose.slides/bullettype).

**Επιστρέφει:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [BulletType](../../com.aspose.slides/bullettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

Επιστρέφει ή ορίζει το χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή  char .

**Επιστρέφει:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Επιστρέφει ή ορίζει το χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή  char .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Η τιμή Float.NaN καθορίζει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/Εγγραφή  float .

--------------------

Μία αρνητική τιμή ύψους σημαίνει ότι το ύψος δίνεται σε μονάδες σημείου και μια θετική τιμή σημαίνει ότι το ύψος είναι ποσοστό του περιβάλλοντος κειμένου.

**Επιστρέφει:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Η τιμή Float.NaN καθορίζει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/Εγγραφή  float .

--------------------

Μία αρνητική τιμή ύψους σημαίνει ότι το ύψος δίνεται σε μονάδες σημείου και μια θετική τιμή σημαίνει ότι το ύψος είναι ποσοστό του περιβάλλοντος κειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Επιστρέφει τη μορφή χρώματος μιας κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή  short .

**Επιστρέφει:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή  short .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Επιστρέφει:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** εάν η κουκίδα έχει δικό της χρώμα και **NullableBool.False** εάν η κουκίδα κληρονομεί χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** εάν η κουκίδα έχει δικό της χρώμα και **NullableBool.False** εάν η κουκίδα κληρονομεί χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** εάν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool.False** εάν η κουκίδα κληρονομεί γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool.True** εάν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool.False** εάν η κουκίδα κληρονομεί γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονόμηση. Μόνο για ανάγνωση [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Επιστρέφει:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Ορίζει τις προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Εσοχή παραγράφου και το αριστερό περιθώριο όταν οι κουκίδες είναι ενεργοποιημένες (όπως κάνει το PowerPoint όταν ενεργοποιούνται οι κουκίδες/αρίθμηση παραγράφου). Εάν οι κουκίδες είναι απενεργοποιημένες, τότε απλώς επαναρυθμίζει το Εσοχή παραγράφου και το αριστερό περιθώριο (όπως κάνει το PowerPoint όταν απενεργοποιούνται οι κουκίδες/αρίθμηση παραγράφου). Οι μετατοπίσεις εσοχής εφαρμόζονται σε σχέση με το τρέχον περιβάλλον κουκίδας - IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετατοπίσεις εσοχής εφαρμόζονται στην αποτελεσματική Εσοχή και το αριστερό περιθώριο της τρέχουσας παραγράφου (καθιστώντας τις τιμές τοπικές).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την εφαρμοσμένη κληρονόμηση.

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - Ένα [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long