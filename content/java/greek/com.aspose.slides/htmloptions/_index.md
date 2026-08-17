---
title: HtmlOptions
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά επιλογές εξαγωγής HTML.
type: docs
url: /el/com.aspose.slides/htmloptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Αναπαριστά επιλογές εξαγωγής HTML.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Δημιουργεί ένα νέο αντικείμενο HtmlOptions που καθορίζει την callback. |
| [HtmlOptions()](#HtmlOptions--) | Δημιουργεί ένα νέο αντικείμενο HtmlOptions για αποθήκευση σε ένα μόνο αρχείο HTML. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το δημιουργούμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το δημιουργούμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Επιστρέφει ή ορίζει το πρότυπο HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Επιστρέφει ή ορίζει το πρότυπο HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λιγκατών. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λιγκατών. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Επιστρέφει ή ορίζει τις επιλογές μορφοποίησης εικόνας διαφάνειας. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Επιστρέφει ή ορίζει τις επιλογές μορφοποίησης εικόνας διαφάνειας. |
| [getJpegQuality()](#getJpegQuality--) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Μια λογική σημαία υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Μια λογική σημαία υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Αληθές για εξαίρεση των χαρακτηριστικών width και height από το κοντέινερ svg - αυτό θα κάνει τη διάταξη αντιδραστική. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Αληθές για εξαίρεση των χαρακτηριστικών width και height από το κοντέινερ svg - αυτό θα κάνει τη διάταξη αντιδραστική. |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Δημιουργεί ένα νέο αντικείμενο HtmlOptions που καθορίζει την callback.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Αντικείμενο callback που ελέγχει την αποθήκευση του έργου. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Δημιουργεί ένα νέο αντικείμενο HtmlOptions για αποθήκευση σε ένα μόνο αρχείο HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

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

Καθορίζει εάν το δημιουργούμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Καθορίζει εάν το δημιουργούμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Επιστρέφει ή ορίζει το πρότυπο HTML. Ανάγνωση/εγγραφή [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Επιστρέφει:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Επιστρέφει ή ορίζει το πρότυπο HTML. Ανάγνωση/εγγραφή [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λιγκατών. Όταν οριστεί σε true, οι λιγκατές θα απενεργοποιηθούν στο τελικό αποτέλεσμα. Από προεπιλογή, αυτή η ιδιότητα είναι false.

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

**Επιστρέφει:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λιγκατών. Όταν οριστεί σε true, οι λιγκατές θα απενεργοποιηθούν στο τελικό αποτέλεσμα. Από προεπιλογή, αυτή η ιδιότητα είναι false.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Επιστρέφει ή ορίζει τις επιλογές μορφοποίησης εικόνας διαφάνειας. Ανάγνωση/εγγραφή [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Επιστρέφει:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Επιστρέφει ή ορίζει τις επιλογές μορφοποίησης εικόνας διαφάνειας. Ανάγνωση/εγγραφή [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte.

Έχει επίδραση μόνο όταν ένα έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **95**.

**Επιστρέφει:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte.

Έχει επίδραση μόνο όταν ένα έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **95**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Αναπαριστά το επίπεδο συμπίεσης των εικόνων.

**Επιστρέφει:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Αναπαριστά το επίπεδο συμπίεσης των εικόνων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Μια λογική σημαία υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν false, θα σειριοποιηθούν στο έγγραφο (που μπορεί ενδεχομένως να οδηγήσει σε μεγαλύτερο αρχείο)

**Επιστρέφει:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Μια λογική σημαία υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν false, θα σειριοποιηθούν στο έγγραφο (που μπορεί ενδεχομένως να οδηγήσει σε μεγαλύτερο αρχείο)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

Αληθές για εξαίρεση των χαρακτηριστικών width και height από το κοντέινερ svg - αυτό θα κάνει τη διάταξη αντιδραστική. Ψευδές - σε άλλη περίπτωση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

Αληθές για εξαίρεση των χαρακτηριστικών width και height από το κοντέινερ svg - αυτό θα κάνει τη διάταξη αντιδραστική. Ψευδές - σε άλλη περίπτωση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |