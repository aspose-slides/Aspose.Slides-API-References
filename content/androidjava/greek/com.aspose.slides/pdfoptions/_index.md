---
title: PdfOptions
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή Pdf.
type: docs
url: /el/com.aspose.slides/pdfoptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή Pdf.

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
>      // Ορίζει τη συμπεριφορά για τα μετααρχεία
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
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Δημιουργεί ένα αντικείμενο της κλάσης PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ορίζει κωδικό πρόσβασης PDF και άδειες πρόσβασης
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
>          // Ορίζει τον τύπο και το μέγεθος της διαφάνειας
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
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getTextCompression()](#getTextCompression--) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου. |
| [setTextCompression(int value)](#setTextCompression-int-) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Δηλώνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλογής) για κάθε εικόνα πρέπει να επιλεχθεί αυτόματα. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Δηλώνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλογής) για κάθε εικόνα πρέπει να επιλεχθεί αυτόματα. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Καθορίζει εάν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Καθορίζει εάν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Επιστρέφει ή ορίζει έναν πίνακα με όνομα χρήστη ορισμένων οικογενειών γραμματοσειρών που το Aspose.Slides θα θεωρεί κοινές. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Επιστρέφει ή ορίζει έναν πίνακα με όνομα χρήστη ορισμένων οικογενειών γραμματοσειρών που το Aspose.Slides θα θεωρεί κοινές. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Καθορίζει εάν όλα τα χαρακτήρες της γραμματοσειράς θα ενσωματωθούν ή μόνο ένα υποσύνολο. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Καθορίζει εάν όλα τα χαρακτήρα της γραμματοσειράς θα ενσωματωθούν ή μόνο ένα υποσύνολο. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Δηλώνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Δηλώνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. |
| [getJpegQuality()](#getJpegQuality--) | Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [getCompliance()](#getCompliance--) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. |
| [setCompliance(int value)](#setCompliance-int-) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. |
| [getPassword()](#getPassword--) | Ρύθμιση κωδικού πρόσβασης χρήστη για προστασία του εγγράφου PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ρύθμιση κωδικού πρόσβασης χρήστη για προστασία του εγγράφου PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης θα χορηγηθούν όταν το έγγραφο ανοιχτεί με πρόσβαση χρήστη. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης θα χορηγηθούν όταν το έγγραφο ανοιχτεί με πρόσβαση χρήστη. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Αληθές για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Αληθές για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Επιστρέφει ή ορίζει τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Επιστρέφει ή ορίζει τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Αληθές για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Αληθές για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Λαμβάνει ή ορίζει το διαφανές χρώμα της εικόνας. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Λαμβάνει ή ορίζει το διαφανές χρώμα της εικόνας. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα αν είναι αληθές. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα αν είναι αληθές. |
| [getIncludeOleData()](#getIncludeOleData--) | Αληθές για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Αληθές για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Προεπιλεγμένος κατασκευαστής.

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

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου. Ανάγνωση/εγγραφή [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Η προεπιλογή είναι [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Επιστρέφει:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου. Ανάγνωση/εγγραφή [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

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

Δηλώνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλογής) για κάθε εικόνα πρέπει να επιλεχθεί αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεχθεί ο καταλληλότερος αλγόριθμος συμπίεσης, με αποτέλεσμα μικρότερο μέγεθος του τελικού εγγράφου PDF.

--------------------

Η επιλογή βέλτιστης αναλογίας συμπίεσης εικόνας απαιτεί σημαντικούς υπολογιστικούς πόρους και επιπλέον μνήμη RAM, και είναι false από προεπιλογή.

--------------------

Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Δηλώνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλογής) για κάθε εικόνα πρέπει να επιλεχθεί αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεχθεί ο καταλληλότερος αλγόριθμος συμπίεσης, με αποτέλεσμα μικρότερο μέγεθος του τελικού εγγράφου PDF.

--------------------

Η επιλογή βέλτιστης αναλογίας συμπίεσης εικόνας απαιτεί σημαντικούς υπολογιστικούς πόρους και επιπλέον μνήμη RAM, και είναι false από προεπιλογή.

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

Καθορίζει εάν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). Οι γραμματοσειρές για κωδικούς μεγαλύτερους από 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές PDF και επιπρόσθετες γραμματοσειρές ορισμένες από τον χρήστη. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Επιστρέφει:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Καθορίζει εάν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). Οι γραμματοσειρές για κωδικούς μεγαλύτερους από 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές PDF και επιπρόσθετες γραμματοσειρές ορισμένες από τον χρήστη. Ανάγνωση/εγγραφή boolean.

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

Επιστρέφει ή ορίζει έναν πίνακα με όνομα χρήστη ορισμένων οικογενειών γραμματοσειρών που το Aspose.Slides θα θεωρεί κοινές. Ανάγνωση/εγγραφή String[].

**Επιστρέφει:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Επιστρέφει ή ορίζει έναν πίνακα με όνομα χρήστη ορισμένων οικογενειών γραμματοσειρών που το Aspose.Slides θα θεωρεί κοινές. Ανάγνωση/εγγραφή String[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Καθορίζει εάν όλα τα χαρακτήρες της γραμματοσειράς θα ενσωματωθούν ή μόνο ένα υποσύνολο. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Καθορίζει εάν όλα τα χαρακτήρες της γραμματοσειράς θα ενσωματωθούν ή μόνο ένα υποσύνολο. Ανάγνωση/εγγραφή boolean.

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

Δηλώνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο τελικό PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Δηλώνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο τελικό PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

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

Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte.

--------------------

Έχει επίδραση μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή ορίσετε την ποιότητα των εικόνων μέσα σε έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει υψηλότερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **100**.

**Επιστρέφει:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Επιστρέφει ή ορίζει τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte.

--------------------

Έχει επίδραση μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή ορίσετε την ποιότητα των εικόνων μέσα σε έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει υψηλότερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **100**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. Ανάγνωση/εγγραφή [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Η προεπιλογή είναι [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Επιστρέφει:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. Ανάγνωση/εγγραφή [PdfCompliance](../../com.aspose.slides/pdfcompliance).

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

Ρύθμιση κωδικού πρόσβασης χρήστη για προστασία του εγγράφου PDF. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Ρύθμιση κωδικού πρόσβασης χρήστη για προστασία του εγγράφου PDF. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης θα χορηγηθούν όταν το έγγραφο ανοιχτεί με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης θα χορηγηθούν όταν το έγγραφο ανοιχτεί με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Αληθές για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστισμένες εικόνες. Εάν SaveMetafilesAsPng οριστεί σε true, το πηγαίο Metafile μετατρέπεται σε μορφή Png και αποθηκεύεται στο PDF ως ραστισμένη εικόνα. Εάν SaveMetafilesAsPng οριστεί σε false, το πηγαίο Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, μπορεί να προκύψει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Εάν το Metafile μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να προκύψουν προβλήματα απόδοσης στο πρόγραμμα προβολής PDF.

**Επιστρέφει:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Αληθές για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστισμένες εικόνες. Εάν SaveMetafilesAsPng οριστεί σε true, το πηγαίο Metafile μετατρέπεται σε μορφή Png και αποθηκεύεται στο PDF ως ραστισμένη εικόνα. Εάν SaveMetafilesAsPng οριστεί σε false, το πηγαίο Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, μπορεί να προκύψει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Εάν το Metafile μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να προκύψουν προβλήματα απόδοσης στο πρόγραμμα προβολής PDF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Επιστρέφει ή ορίζει τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτής της παραμέτρου εξαρτάται από διάφορους παράγοντες. Ο αλγόριθμος προσπαθεί να επιλέξει το βέλτιστο μέγεθος εξόδου της εικόνας βάσει της τιμής της ιδιότητας, του μεγέθους της πηγαίας εικόνας και του μεγέθους του πλαισίου της εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται χρήση βήματος 16 ή 32 για ορατό αποτέλεσμα.

--------------------

Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.

Η προεπιλεγμένη τιμή είναι **96**.

**Επιστρέφει:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Επιστρέφει ή ορίζει τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτής της παραμέτρου εξαρτάται από διάφορους παράγοντες. Ο αλγόριθμος προσπαθεί να επιλέξει το βέλτιστο μέγεθος εξόδου της εικόνας βάσει της τιμής της ιδιότητας, του μεγέθους της πηγαίας εικόνας και του μεγέθους του πλαισίου της εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται χρήση βήματος 16 ή 32 για ορατό αποτέλεσμα.

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

Αληθές για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Αληθές για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Λαμβάνει ή ορίζει το διαφανές χρώμα της εικόνας.

Τιμή: Το χρώμα της διαφανούς εικόνας.

**Επιστρέφει:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Λαμβάνει ή ορίζει το διαφανές χρώμα της εικόνας.

Τιμή: Το χρώμα της διαφανούς εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα αν είναι αληθές.

**Επιστρέφει:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα αν είναι αληθές.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Αληθές για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean.

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

Η προεπιλογή είναι **false** .

**Επιστρέφει:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Αληθές για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean.

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

Η προεπιλογή είναι **false** .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |