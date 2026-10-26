---
title: IBulletFormat
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει ιδιότητες μορφοποίησης κουκίδων παραγράφου.
type: docs
url: /el/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Αντιπροσωπεύει ιδιότητες μορφοποίησης κουκίδων παραγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setType(byte value)](#setType-byte-) | Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getChar()](#getChar--) | Επιστρέφει ή ορίζει το σύμβολο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setChar(char value)](#setChar-char-) | Επιστρέφει ή ορίζει το σύμβολο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getFont()](#getFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getHeight()](#getHeight--) | Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [setHeight(float value)](#setHeight-float-) | Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getColor()](#getColor--) | Επιστρέφει τη μορφή χρώματος μιας κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. |
| [isBulletHardColor()](#isBulletHardColor--) | Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [isBulletHardFont()](#isBulletHardFont--) | Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ορίζει προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν οι κουκίδες είναι ενεργοποιημένες (όπως κάνει το PowerPoint εάν ενεργοποιηθούν οι κουκίδες/αρίθμηση παραγράφων). |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την κληρονομικότητα εφαρμοσμένη. |
### getType() {#getType--}
```
public abstract byte getType()
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [BulletType](../../com.aspose.slides/bullettype).

**Επιστρέφει:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [BulletType](../../com.aspose.slides/bullettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Επιστρέφει ή ορίζει το σύμβολο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή char.

**Επιστρέφει:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Επιστρέφει ή ορίζει το σύμβολο της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή char.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή Float.NaN καθορίζει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος της κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή Float.NaN καθορίζει ότι η κουκίδα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Επιστρέφει τη μορφή χρώματος μιας κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονομικότητα. Μόνο ανάγνωση [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Επιστρέφει:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή short.

**Επιστρέφει:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή short.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Επιστρέφει:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** εάν η κουκίδα έχει δικό της χρώμα και **NullableBool#False** εάν η κουκίδα κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Καθορίζει εάν η κουκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** εάν η κουκίδα έχει δικό της χρώμα και **NullableBool#False** εάν η κουκίδα κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** εάν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool#False** εάν η κουκίδα κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Καθορίζει εάν η κουκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. **NullableBool#True** εάν η κουκίδα έχει δική της γραμματοσειρά και **NullableBool#False** εάν η κουκίδα κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Ορίζει προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν οι κουκίδες είναι ενεργοποιημένες (όπως κάνει το PowerPoint εάν ενεργοποιηθούν οι κουκίδες/αρίθμηση παραγράφων). Εάν οι κουκίδες είναι απενεργοποιημένες, τότε επαναφέρει μόνο το Indent και το MarginLeft της παραγράφου (όπως κάνει το PowerPoint εάν απενεργοποιηθούν οι κουκίδες/αρίθμηση παραγράφων). Οι μετατοπίσεις των εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο κουκίδας – IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (για να γίνουν οι τιμές αποτέλεσμα τοπικές τιμές).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την κληρονομικότητα εφαρμόζουσα.

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