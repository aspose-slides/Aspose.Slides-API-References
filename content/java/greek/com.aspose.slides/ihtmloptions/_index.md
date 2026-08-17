---
title: IHtmlOptions
second_title: Aspose.Slides για την αναφορά API της Java
description: Αναπαριστά τις επιλογές εξαγωγής HTML.
type: docs
url: /el/com.aspose.slides/ihtmloptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Αναπαριστά τις επιλογές εξαγωγής HTML.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Επιστρέφει ή ορίζει το πρότυπο HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Επιστρέφει ή ορίζει το πρότυπο HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getJpegQuality()](#getJpegQuality--) | Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός εγγράφου PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός εγγράφου PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Μια λογική σημαία υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Μια λογική σημαία υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True για να εξαιρέσετε τα χαρακτηριστικά πλάτους και ύψους από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη ανταποκρινόμενη. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True για να εξαιρέσετε τα χαρακτηριστικά πλάτους και ύψους από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη ανταποκρινόμενη. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Λαμβάνει ή ορίζει τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση λιγάρων. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Λαμβάνει ή ορίζει τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση λιγάρων. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |
### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```


Επιστρέφει ή ορίζει το πρότυπο HTML. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Επιστρέφει:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```


Επιστρέφει ή ορίζει το πρότυπο HTML. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```


Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Επιστρέφει:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```


Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```


Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός εγγράφου PDF. Read/write byte.

--------------------

Έχει αντίκτυπο μόνο όταν ένα έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει την χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει την καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **95**.

**Επιστρέφει:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```


Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός εγγράφου PDF. Read/write byte.

--------------------

Έχει αντίκτυπο μόνο όταν ένα έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει την χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει την καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **95**.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


Αναπαριστά το επίπεδο συμπίεσης των εικόνων Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Επιστρέφει:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


Αναπαριστά το επίπεδο συμπίεσης των εικόνων Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


Μια λογική σημαία υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα μέρη θα αφαιρεθούν· εάν false, θα παραμείνουν στο έγγραφο (πράγμα που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Read/write boolean.

**Επιστρέφει:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


Μια λογική σημαία υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα μέρη θα αφαιρεθούν· εάν false, θα παραμείνουν στο έγγραφο (πράγμα που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Read/write boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```


True για να εξαιρέσετε τα χαρακτηριστικά πλάτους και ύψους από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη ανταποκρινόμενη. False - διαφορετικά. Read/write boolean.

**Επιστρέφει:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```


True για να εξαιρέσετε τα χαρακτηριστικά πλάτους και ύψους από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη ανταποκρινόμενη. False - διαφορετικά. Read/write boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


Λαμβάνει ή ορίζει τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση λιγάρων. Όταν οριστεί σε true, οι λιγάροι θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, η ιδιότητα είναι false.

--------------------

> ```
> Παράδειγμα:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


Λαμβάνει ή ορίζει τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση λιγάρων. Όταν οριστεί σε true, οι λιγάροι θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, η ιδιότητα είναι false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
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
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)