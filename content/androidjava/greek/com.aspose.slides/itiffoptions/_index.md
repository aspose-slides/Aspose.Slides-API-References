---
title: ITiffOptions
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.
type: docs
url: /el/com.aspose.slides/itiffoptions/
---
**Όλες οι Εφαρμοσμένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImageSize()](#getImageSize--) | Καθορίζει το μέγεθος μιας δημιουργημένης εικόνας TIFF. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Καθορίζει το μέγεθος μιας δημιουργημένης εικόνας TIFF. |
| [getDpiX()](#getDpiX--) | Καθορίζει την οριζόντια ανάλυση σε σημεία ανά ίντσα. |
| [setDpiX(long value)](#setDpiX-long-) | Καθορίζει την οριζόντια ανάλυση σε σημεία ανά ίντσα. |
| [getDpiY()](#getDpiY--) | Καθορίζει την κάθετη ανάλυση σε σημεία ανά ίντσα. |
| [setDpiY(long value)](#setDpiY-long-) | Καθορίζει την κάθετη ανάλυση σε σημεία ανά ίντσα. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το δημιουργημένο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το δημιουργημένο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getCompressionType()](#getCompressionType--) | Καθορίζει τον τύπο συμπίεσης. |
| [setCompressionType(int value)](#setCompressionType-int-) | Καθορίζει τον τύπο συμπίεσης. |
| [getPixelFormat()](#getPixelFormat--) | Καθορίζει τη μορφή pixel για τις δημιουργημένες εικόνες. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Καθορίζει τη μορφή pixel για τις δημιουργημένες εικόνες. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ίνκ σε εξαγόμενο έγγραφο. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Καθορίζει το μέγεθος μιας δημιουργημένης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των δημιουργημένων εικόνων θα υπολογίζονται βάσει του μεγέθους των διαφανειών της παρουσίασης. Ανάγνωση/εγγραφή [Size](../../com.aspose.slides.android/size).

**Επιστρέφει:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Καθορίζει το μέγεθος μιας δημιουργημένης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των δημιουργημένων εικόνων θα υπολογίζονται βάσει του μεγέθους των διαφανειών της παρουσίασης. Ανάγνωση/εγγραφή [Size](../../com.aspose.slides.android/size).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Καθορίζει την οριζόντια ανάλυση σε σημεία ανά ίντσα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Καθορίζει την οριζόντια ανάλυση σε σημεία ανά ίντσα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Καθορίζει την κάθετη ανάλυση σε σημεία ανά ίντσα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Καθορίζει την κάθετη ανάλυση σε σημεία ανά ίντσα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Καθορίζει αν το δημιουργημένο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Καθορίζει αν το δημιουργημένο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Καθορίζει τον τύπο συμπίεσης. Ανάγνωση/εγγραφή [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Επιστρέφει:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Καθορίζει τον τύπο συμπίεσης. Ανάγνωση/εγγραφή [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Καθορίζει τη μορφή pixel για τις δημιουργημένες εικόνες. Ανάγνωση/εγγραφή [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Επιστρέφει:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Καθορίζει τη μορφή pixel για τις δημιουργημένες εικόνες. Ανάγνωση/εγγραφή [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

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
> Παράδειγμα:
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

Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή εφαρμόζεται μόνο εάν ο CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) είναι ορισμένος σε [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ή [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Ανάγνωση/εγγραφή [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Η προεπιλογή είναι [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή εφαρμόζεται μόνο εάν ο CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) είναι ορισμένος σε [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ή [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Ανάγνωση/εγγραφή [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Η προεπιλογή είναι [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ίνκ σε εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)