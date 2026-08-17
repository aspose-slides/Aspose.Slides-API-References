---
title: TiffOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.
type: docs
url: /el/com.aspose.slides/tiffoptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Αποθήκευση της παρουσίασης σε έγγραφο TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο Presentation
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Δημιουργεί μια κλάση TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Ορίζει τον τύπο συμπίεσης
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Τύποι Συμπίεσης
>      // Default - Καθορίζει το προεπιλεγμένο σχήμα συμπίεσης (LZW).
>      // None - Καθορίζει ότι δεν υπάρχει συμπίεση.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Το βάθος εξαρτάται από τον τύπο συμπίεσης και δεν μπορεί να οριστεί χειροκίνητα.
>      // Η μονάδα ανάλυσης είναι πάντα ίση με 2 (κουκκίδες ανά ίντσα)
>      // Ορισμός DPI εικόνας
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Ορισμός Μεγέθους Εικόνας
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Αποθήκευση της παρουσίασης σε TIFF με καθορισμένο μέγεθος εικόνας
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο Presentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat περιέχει τις ακόλουθες τιμές (όπως φαίνεται από την τεκμηρίωση):
>      //Format1bppIndexed; // 1 bits ανά pixel, με ευρετήριο.
>      //Format4bppIndexed; // 4 bits ανά pixel, με ευρετήριο.
>      //Format8bppIndexed; // 8 bits ανά pixel, με ευρετήριο.
>      //Format24bppRgb; // 24 bits ανά pixel, RGB.
>      //Format32bppArgb; // 32 bits ανά pixel, ARGB.
> 
>      // Αποθήκευση της παρουσίασης σε TIFF με καθορισμένο μέγεθος εικόνας
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Προεπιλεγμένος κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυμμένες διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυμμένες διαφάνειες ή όχι. |
| [getImageSize()](#getImageSize--) | Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. |
| [getDpiX()](#getDpiX--) | Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα. |
| [setDpiX(long value)](#setDpiX-long-) | Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα. |
| [getDpiY()](#getDpiY--) | Καθορίζει την κάθετη ανάλυση σε κουκκίδες ανά ίντσα. |
| [setDpiY(long value)](#setDpiY-long-) | Καθορίζει την κάθετη ανάλυση σε κουκκίδες ανά ίντσα. |
| [getCompressionType()](#getCompressionType--) | Καθορίζει τον τύπο συμπίεσης. |
| [setCompressionType(int value)](#setCompressionType-int-) | Καθορίζει τον τύπο συμπίεσης. |
| [getPixelFormat()](#getPixelFormat--) | Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Καθορίζει τον αλγόριθμο μετατροπής μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Καθορίζει τον αλγόριθμο μετατροπής μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Προεπιλεγμένος κατασκευαστής.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυμμένες διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυμμένες διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```


Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογιστούν βάσει της τιμής μεγέθους διαφάνειας της παρουσίασης. Ανάγνωση/εγγραφή java.awt.Dimension.

**Επιστρέφει:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```


Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογιστούν βάσει της τιμής μεγέθους διαφάνειας της παρουσίασης. Ανάγνωση/εγγραφή java.awt.Dimension.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Καθορίζει την κάθετη ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Καθορίζει την κάθετη ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Καθορίζει τον τύπο συμπίεσης. Ανάγνωση/εγγραφή [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Επιστρέφει:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Καθορίζει τον τύπο συμπίεσης. Ανάγνωση/εγγραφή [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες. Ανάγνωση/εγγραφή [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Επιστρέφει:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες. Ανάγνωση/εγγραφή [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Παράμετροι:**
| Παράμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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
public final int getBwConversionMode()
```


Καθορίζει τον αλγόριθμο μετατροπής μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν ο CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) είναι ορισμένος σε [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ή [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Ανάγνωση/εγγραφή [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Η προεπιλογή είναι [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public final void setBwConversionMode(int value)
```


Καθορίζει τον αλγόριθμο μετατροπής μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν ο CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) είναι ορισμένος σε [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ή [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Ανάγνωση/εγγραφή [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Η προεπιλογή είναι [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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