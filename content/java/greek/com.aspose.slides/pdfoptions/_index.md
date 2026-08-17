---
title: PdfOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Pdf.
type: docs
url: /el/com.aspose.slides/pdfoptions/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PDF.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Δημιουργεί ένα αντικείμενο της κλάσης PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ορίζει την ποιότητα JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // Ορίζει τη συμπεριφορά για τα metafiles
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Ορίζει το επίπεδο συμπίεσης κειμένου
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Ορίζει το πρότυπο PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Αποθηκεύει την παρουσίαση ως PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Δημιουργεί ένα αντικείμενο της κλάσης Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Δημιουργεί ένα αντικείμενο της κλάσης PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Προσθέτει κρυφές διαφάνειες
>      pdfOptions.setShowHiddenSlides(true);
>      // Αποθηκεύει την παρουσίαση ως PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Δημιουργεί ένα αντικείμενο της κλάσης Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Δημιουργεί ένα αντικείμενο της κλάσης PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ορίζει τον κωδικό πρόσβασης PDF και τα δικαιώματα πρόσβασης
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Αποθηκεύει την παρουσίαση ως PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Ορισμός τύπου διαφάνειας και μεγέθους
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Προεπιλεγμένος κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το δημιουργημένο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το δημιουργημένο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getTextCompression()](#getTextCompression--) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. |
| [setTextCompression(int value)](#setTextCompression-int-) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Δείχνει εάν πρέπει να επιλεγεί αυτόματα η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Δείχνει εάν πρέπει να επιλεγεί αυτόματα η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Καθορίζει αν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κώδικα 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Καθορίζει αν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κώδικα 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Επιστρέφει ή ορίζει έναν πίνακα με ορισθέντα ονόματα οικογενειών γραμματοσειρών που το Aspose.Slides πρέπει να θεωρεί κοινές. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Επιστρέφει ή ορίζει έναν πίνακα με ορισθέντα ονόματα οικογενειών γραμματοσειρών που το Aspose.Slides πρέπει να θεωρεί κοινές. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Καθορίζει αν θα ενσωματωθούν όλοι οι χαρακτήρες της γραμματοσειράς ή μόνο ένα υποσύνολο. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Καθορίζει αν θα ενσωματωθούν όλοι οι χαρακτήρες της γραμματοσειράς ή μόνο ένα υποσύνολο. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφή. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφή. |
| [getJpegQuality()](#getJpegQuality--) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός του PDF εγγράφου. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός του PDF εγγράφου. |
| [getCompliance()](#getCompliance--) | Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο PDF έγγραφο. |
| [setCompliance(int value)](#setCompliance-int-) | Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο PDF έγγραφο. |
| [getPassword()](#getPassword--) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του PDF εγγράφου. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του PDF εγγράφου. |
| [getAccessPermissions()](#getAccessPermissions--) | Περιέχει ένα σύνολο σημάνσεων που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Περιέχει ένα σύνολο σημάνσεων που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων εντός του PDF εγγράφου. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων εντός του PDF εγγράφου. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Αληθές για το σχεδιασμό μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Αληθές για το σχεδιασμό μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Εφαρμόζει το καθορισμένο διαφανές χρώμα στην εικόνα αν είναι αληθές. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Εφαρμόζει το καθορισμένο διαφανές χρώμα στην εικόνα αν είναι αληθές. |
| [getIncludeOleData()](#getIncludeOleData--) | Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Προεπιλεγμένος κατασκευαστής.

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
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Καθορίζει αν το δημιουργημένο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Καθορίζει αν το δημιουργημένο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Ανάγνωση/εγγραφή [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Η προεπιλογή είναι [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Επιστρέφει:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Ανάγνωση/εγγραφή [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Η προεπιλογή είναι [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Δείχνει εάν πρέπει να επιλεγεί αυτόματα η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα. Αν οριστεί σε αληθές, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου PDF εγγράφου.

--------------------

Η επιλογή βέλτιστης αναλογίας συμπίεσης εικόνας είναι υπολογιστικά δαπανηρή και καταναλώνει πρόσθετη μνήμη RAM· αυτή η επιλογή είναι false από προεπιλογή.

--------------------

Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Δείχνει εάν πρέπει να επιλεγεί αυτόματα η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα. Αν οριστεί σε αληθές, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου PDF εγγράφου.

--------------------

Η επιλογή βέλτιστης αναλογίας συμπίεσης εικόνας είναι υπολογιστικά δαπανηρή και καταναλώνει πρόσθετη μνήμη RAM· αυτή η επιλογή είναι false από προεπιλογή.

--------------------

Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Καθορίζει αν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κώδικα 33..127). Οι γραμματοσειρές για κωδικούς μεγαλύτερους του 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές PDF και επιπλέον γραμματοσειρές που ορίζονται από το χρήστη. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Επιστρέφει:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Καθορίζει αν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κώδικα 33..127). Οι γραμματοσειρές για κωδικούς μεγαλύτερους του 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές PDF και επιπλέον γραμματοσειρές που ορίζονται από το χρήστη. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Επιστρέφει ή ορίζει έναν πίνακα με ορισθέντα ονόματα οικογενειών γραμματοσειρών που το Aspose.Slides πρέπει να θεωρεί κοινές. Ανάγνωση/εγγραφή String[].

**Επιστρέφει:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Επιστρέφει ή ορίζει έναν πίνακα με ορισθέντα ονόματα οικογενειών γραμματοσειρών που το Aspose.Slides πρέπει να θεωρεί κοινές. Ανάγνωση/εγγραφή String[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Καθορίζει αν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο ένα υποσύνολο. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Καθορίζει αν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο ένα υποσύνολο. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφή. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφή. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός του PDF εγγράφου. Ανάγνωση/εγγραφή byte.

--------------------

Έχει επίδραση μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων εντός ενός εγγράφου κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει υψηλότερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **100**.

**Επιστρέφει:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG εντός του PDF εγγράφου. Ανάγνωση/εγγραφή byte.

--------------------

Έχει επίδραση μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων εντός ενός εγγράφου κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει υψηλότερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **100**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο PDF έγγραφο. Ανάγνωση/εγγραφή [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Η προεπιλογή είναι [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Επιστρέφει:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο PDF έγγραφο. Ανάγνωση/εγγραφή [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Η προεπιλογή είναι [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του PDF εγγράφου. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του PDF εγγράφου. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Περιέχει ένα σύνολο σημάνσεων που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Περιέχει ένα σύνολο σημάνσεων που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**. Το PDF έγγραφο μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Αν το SaveMetafilesAsPng οριστεί σε true, η πηγή Metafile εικόνας μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Αν το SaveMetafilesAsPng οριστεί σε false, η πηγή Metafile μετατρέπεται σε PDF διανυσματικά γραφικά. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, αν το Metafile μετατραπεί σε PNG, τότε μπορεί να υπάρξει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Αν το Metafile μετατραπεί σε PDF διανυσματικά γραφικά, τότε μπορεί να προκύψουν προβλήματα απόδοσης στο εργαλείο προβολής PDF.

**Επιστρέφει:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**. Το PDF έγγραφο μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Αν το SaveMetafilesAsPng οριστεί σε true, η πηγή Metafile εικόνας μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Αν το SaveMetafilesAsPng οριστεί σε false, η πηγή Metafile μετατρέπεται σε PDF διανυσματικά γραφικά. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, αν το Metafile μετατραπεί σε PNG, τότε μπορεί να υπάρξει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Αν το Metafile μετατραπεί σε PDF διανυσματικά γραφικά, τότε μπορεί να προκύψουν προβλήματα απόδοσης στο εργαλείο προβολής PDF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Αποκτά ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων εντός του PDF εγγράφου. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτής της παραμέτρου εξαρτάται από διάφορους παράγοντες. Ο αλγόριθμος προσπαθεί να επιτύχει το βέλτιστο μέγεθος εξόδου εικόνας σύμφωνα με την τιμή της ιδιότητας, το μέγεθος της πηγής εικόνας και το μέγεθος του πλαισίου εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται να χρησιμοποιείται βήμα 16 ή 32 για ορατό αποτέλεσμα.

--------------------

Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.

Η προεπιλεγμένη τιμή είναι **96**.

**Επιστρέφει:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Αποκτά ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων εντός του PDF εγγράφου. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτής της παραμέτρου εξαρτάται από διάφορους παράγοντες. Ο αλγόριθμος προσπαθεί να επιτύχει το βέλτιστο μέγεθος εξόδου εικόνας σύμφωνα με την τιμή της ιδιότητας, το μέγεθος της πηγής εικόνας και το μέγεθος του πλαισίου εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται να χρησιμοποιείται βήμα 16 ή 32 για ορατό αποτέλεσμα.

--------------------

Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.

Η προεπιλεγμένη τιμή είναι **96**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Αληθές για το σχεδιασμό μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Αληθές για το σχεδιασμό μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας.

Τιμή: Το χρώμα της διαφανούς εικόνας.

**Επιστρέφει:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας.

Τιμή: Το χρώμα της διαφανούς εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Εφαρμόζει το καθορισμένο διαφανές χρώμα στην εικόνα αν είναι αληθές.

**Επιστρέφει:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Εφαρμόζει το καθορισμένο διαφανές χρώμα στην εικόνα αν είναι αληθές.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |