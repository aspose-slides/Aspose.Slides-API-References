---
title: ITiffOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή TIFF.
type: docs
url: /el/com.aspose.slides/itiffoptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή TIFF.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImageSize()](#getImageSize--) | Ορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Ορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. |
| [getDpiX()](#getDpiX--) | Ορίζει την οριζόντια ανάλυση σε κουκίδες ανά ίντσα. |
| [setDpiX(long value)](#setDpiX-long-) | Ορίζει την οριζόντια ανάλυση σε κουκίδες ανά ίντσα. |
| [getDpiY()](#getDpiY--) | Ορίζει την κάθετη ανάλυση σε κουκίδες ανά ίντσα. |
| [setDpiY(long value)](#setDpiY-long-) | Ορίζει την κάθετη ανάλυση σε κουκίδες ανά ίντσα. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Ορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Ορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getCompressionType()](#getCompressionType--) | Ορίζει τον τύπο συμπίεσης. |
| [setCompressionType(int value)](#setCompressionType-int-) | Ορίζει τον τύπο συμπίεσης. |
| [getPixelFormat()](#getPixelFormat--) | Ορίζει τη μορφή εικονοστοιχείου για τις παραγόμενες εικόνες. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Ορίζει τη μορφή εικονοστοιχείου για τις παραγόμενες εικόνες. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Ορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Ορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |

### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

Ορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογίζονται με βάση την τιμή του μεγέθους της διαφάνειας παρουσίασης. Ανάγνωση/Εγγραφή java.awt.Dimension.

**Επιστρέφει:**
java.awt.Dimension

### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

Ορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογίζονται με βάση την τιμή του μεγέθους της διαφάνειας παρουσίασης. Ανάγνωση/Εγγραφή java.awt.Dimension.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Ορίζει την οριζόντια ανάλυση σε κουκίδες ανά ίντσα. Ανάγνωση/Εγγραφή long.

**Επιστρέφει:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Ορίζει την οριζόντια ανάλυση σε κουκίδες ανά ίντσα. Ανάγνωση/Εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Ορίζει την κάθετη ανάλυση σε κουκίδες ανά ίντσα. Ανάγνωση/Εγγραφή long.

**Επιστρέφει:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Ορίζει την κάθετη ανάλυση σε κουκίδες ανά ίντσα. Ανάγνωση/Εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Ορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Ορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Ορίζει τον τύπο συμπίεσης. Ανάγνωση/Εγγραφή [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Επιστρέφει:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Ορίζει τον τύπο συμπίεσης. Ανάγνωση/Εγγραφή [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Ορίζει τη μορφή εικονοστοιχείου για τις παραγόμενες εικόνες. Ανάγνωση/Εγγραφή [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Επιστρέφει:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Ορίζει τη μορφή εικονοστοιχείου για τις παραγόμενες εικόνες. Ανάγνωση/Εγγραφή [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Ορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν ο CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) είναι ορισμένος σε [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ή [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Ανάγνωση/Εγγραφή [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Η προεπιλογή είναι [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

Ορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν ο CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) είναι ορισμένος σε [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ή [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Ανάγνωση/Εγγραφή [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Η προεπιλογή είναι [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)