---
title: IBulletFormat
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά τις ιδιότητες μορφοποίησης κουκίδας παραγράφου.
type: docs
url: /el/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Αναπαριστά τις ιδιότητες μορφοποίησης κουκίδας παραγράφου.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
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
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονόμηση. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. |
| [isBulletHardColor()](#isBulletHardColor--) | Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [isBulletHardFont()](#isBulletHardFont--) | Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ορίζει προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν οι κουκίδες είναι ενεργές (όπως κάνει το PowerPoint όταν ενεργοποιούνται οι κουκίδες/αρίθμηση). |
| [getEffective()](#getEffective--) | Λαμβάνει δεδομένα αποτελεσματικής μορφοποίησης κουκίδας με την κληρονόμηση εφαρμόστηκε. |

### getType() {#getType--}
```
public abstract byte getType()
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/εγγραφή [BulletType](../../com.aspose.slides/bullettype).

**Επιστρέφει:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/εγγραφή [BulletType](../../com.aspose.slides/bullettype).

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

Επιστρέφει ή ορίζει το χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/εγγραφή char.

**Επιστρέφει:**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Επιστρέφει ή ορίζει το χαρακτήρα της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/εγγραφή char.

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Η τιμή Float.NaN καθορίζει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Η τιμή Float.NaN καθορίζει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Επιστρέφει τη μορφή χρώματος μιας κουκίδας μιας παραγράφου χωρίς κληρονόμηση. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονόμηση. Μόνο για ανάγνωση [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Επιστρέφει:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. Ανάγνωση/εγγραφή short.

**Επιστρέφει:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονόμηση. Ανάγνωση/εγγραφή short.

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. Ανάγνωση/εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Επιστρέφει:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονόμηση. Ανάγνωση/εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** αν η κουκίδα έχει δικό της χρώμα και **NullableBool#False** αν η κουκίδα κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** αν η κουκίδα έχει δικό της χρώμα και **NullableBool#False** αν η κουκίδα κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** αν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool#False** αν η κουκίδα κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** αν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool#False** αν η κουκίδα κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Ορίζει προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν οι κουκίδες είναι ενεργές (όπως κάνει το PowerPoint όταν ενεργοποιούνται οι κουκίδες/αρίθμηση). Εάν οι κουκίδες είναι ανενεργές, επαναφέρει απλώς το Indent και MarginLeft της παραγράφου (όπως κάνει το PowerPoint όταν απενεργοποιούνται οι κουκίδες/αρίθμηση). Οι μετατοπίσεις των εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο της κουκίδας – IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (κάνουν τις τιμές τοπικές).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Λαμβάνει δεδομένα αποτελεσματικής μορφοποίησης κουκίδας με την κληρονόμηση εφαρμόστηκε.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να λαμβάνονται ορισμένες ιδιότητες αποτελεσματικής μορφοποίησης κουκίδας.
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