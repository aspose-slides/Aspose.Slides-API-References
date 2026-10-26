---
title: IHtmlOptions
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά επιλογές εξαγωγής HTML.
type: docs
url: /el/com.aspose.slides/ihtmloptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Αναπαριστά επιλογές εξαγωγής HTML.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Επιστρέφει ή ορίζει το πρότυπο HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Επιστρέφει ή ορίζει το πρότυπο HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getJpegQuality()](#getJpegQuality--) | Επιστρέφει ή ορίζει την τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Επιστρέφει ή ορίζει την τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Αναπαριστά το επίπεδο συμπίεσης εικόνων Ανάγνωση/Εγγραφή [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αναπαριστά το επίπεδο συμπίεσης εικόνων Ανάγνωση/Εγγραφή [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Μια λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Μια λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Αληθές για να εξαιρεθούν τα χαρακτηριστικά width και height από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη προσαρμοστική. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Αληθές για να εξαιρεθούν τα χαρακτηριστικά width και height από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη προσαρμοστική. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Επιστρέφει ή ορίζει το πρότυπο HTML. Ανάγνωση/Εγγραφή [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Επιστρέφει:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Επιστρέφει ή ορίζει το πρότυπο HTML. Ανάγνωση/Εγγραφή [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. Ανάγνωση/Εγγραφή [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Επιστρέφει:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. Ανάγνωση/Εγγραφή [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλεγμένη τιμή είναι ψευδής.

**Επιστρέφει:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλεγμένη τιμή είναι ψευδής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/Εγγραφή byte.

Ισχύει μόνο όταν ένα έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου το 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και το 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **95**.

**Επιστρέφει:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/Εγγραφή byte.

Ισχύει μόνο όταν ένα έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου το 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και το 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **95**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Αναπαριστά το επίπεδο συμπίεσης εικόνων Ανάγνωση/Εγγραφή [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Επιστρέφει:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Αναπαριστά το επίπεδο συμπίεσης εικόνων Ανάγνωση/Εγγραφή [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Μια λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν είναι αληθές, τα περικομμένα τμήματα θα αφαιρεθούν· εάν είναι ψευδές, θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Μια λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν είναι αληθές, τα περικομμένα τμήματα θα αφαιρεθούν· εάν είναι ψευδές, θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

Αληθές για να εξαιρεθούν τα χαρακτηριστικά width και height από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη προσαρμοστική. Ψευδές - αλλιώς. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

Αληθές για να εξαιρεθούν τα χαρακτηριστικά width και height από το κοντέινερ SVG - αυτό θα κάνει τη διάταξη προσαρμοστική. Ψευδές - αλλιώς. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων (ligatures). Όταν οριστεί σε αληθές, οι συνδέσεις θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι ψευδής.

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


**Επιστρέφει:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων (ligatures). Όταν οριστεί σε αληθές, οι συνδέσεις θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι ψευδής.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)