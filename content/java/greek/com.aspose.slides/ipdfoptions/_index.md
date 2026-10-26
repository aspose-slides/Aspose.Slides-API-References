---
title: IPdfOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Pdf.
type: docs
url: /el/com.aspose.slides/ipdfoptions/
---
**Όλοι οι Υλοποιημένοι Διεπαφείς:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PDF.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. |
| [setTextCompression(int value)](#setTextCompression-int-) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Υποδεικνύει αν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Υποδεικνύει αν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Αληθές για την ένθεση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Αληθές για την ένθεση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Επιστρέφει ή ορίζει έναν πίνακα ονομάτων γραμματοσειρών που ορίζονται από τον χρήστη και που το Aspose.Slides πρέπει να θεωρεί κοινά. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Επιστρέφει ή ορίζει έναν πίνακα ονομάτων γραμματοσειρών που ορίζονται από τον χρήστη και που το Aspose.Slides πρέπει να θεωρεί κοινά. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Καθορίζει αν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το υποσύνολο που χρησιμοποιείται. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Καθορίζει αν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το υποσύνολο που χρησιμοποιείται. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Υποδεικνύει αν το κείμενο πρέπει να ραστεροποιηθεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Υποδεικνύει αν το κείμενο πρέπει να ραστεροποιηθεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. |
| [getJpegQuality()](#getJpegQuality--) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF. |
| [getCompliance()](#getCompliance--) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. |
| [setCompliance(int value)](#setCompliance-int-) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. |
| [getPassword()](#getPassword--) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Περιλαμβάνει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Περιλαμβάνει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Αληθές για τη σχεδίαση μαύρου περιγράμματος γύρω από κάθε διαφάνεια. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Αληθές για τη σχεδίαση μαύρου περιγράμματος γύρω από κάθε διαφάνεια. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν είναι αληθές. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν είναι αληθές. |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getIncludeOleData()](#getIncludeOleData--) | Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Ανάγνωση/εγγραφή [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Η προεπιλογή είναι [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Επιστρέφει:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
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
public abstract boolean getBestImagesCompressionRatio()
```

Υποδεικνύει αν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, οδηγώντας σε μικρότερο μέγεθος του παραγόμενου εγγράφου PDF.

--------------------

Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και απαιτεί επιπλέον μνήμη RAM, και αυτή η επιλογή είναι false από προεπιλογή.

--------------------

Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Υποδεικνύει αν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, οδηγώντας σε μικρότερο μέγεθος του παραγόμενου εγγράφου PDF.

--------------------

Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και απαιτεί επιπλέον μνήμη RAM, και αυτή η επιλογή είναι false από προεπιλογή.

--------------------

Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

Αληθές για την ένθεση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. Οι γραμματοσειρές για κωδικούς χαρακτήρων μεγαλύτερους από 127 είναι πάντα ενσωματωμένες. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Επιστρέφει:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Αληθές για την ένθεση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. Οι γραμματοσειρές για κωδικούς χαρακτήρων μεγαλύτερους από 127 είναι πάντα ενσωματωμένες. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Επιστρέφει ή ορίζει έναν πίνακα ονομάτων γραμματοσειρών που ορίζονται από τον χρήστη και που το Aspose.Slides πρέπει να θεωρεί κοινά. Ανάγνωση/εγγραφή String[].

**Επιστρέφει:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Επιστρέφει ή ορίζει έναν πίνακα ονομάτων γραμματοσειρών που ορίζονται από τον χρήστη και που το Aspose.Slides πρέπει να θεωρεί κοινά. Ανάγνωση/εγγραφή String[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Καθορίζει αν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το υποσύνολο που χρησιμοποιείται. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Καθορίζει αν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το υποσύνολο που χρησιμοποιείται. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Υποδεικνύει αν το κείμενο πρέπει να ραστεροποιηθεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Υποδεικνύει αν το κείμενο πρέπει να ραστεροποιηθεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF. Ανάγνωση/εγγραφή byte.

--------------------

Ισχύει μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλογή είναι **100**.

**Επιστρέφει:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF. Ανάγνωση/εγγραφή byte.

--------------------

Ισχύει μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση.

Η προεπιλογή είναι **100**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. Ανάγνωση/εγγραφή [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Η προεπιλογή είναι [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Επιστρέφει:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
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
public abstract String getPassword()
```

Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Περιλαμβάνει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Περιλαμβάνει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Εάν το SaveMetafilesAsPng είναι true, τότε η πηγή Metafile μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Εάν το SaveMetafilesAsPng είναι false, η πηγή Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, αν το Metafile μετατραπεί σε PNG, μπορεί να προκύψει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Αν το Metafile μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να προκύψουν προβλήματα απόδοσης στο εργαλείο προβολής PDF.

**Επιστρέφει:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Εάν το SaveMetafilesAsPng είναι true, τότε η πηγή Metafile μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Εάν το SaveMetafilesAsPng είναι false, η πηγή Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, αν το Metafile μετατραπεί σε PNG, μπορεί να προκύψει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Αν το Metafile μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να προκύψουν προβλήματα απόδοσης στο εργαλείο προβολής PDF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτού του παραμέτρου εξαρτάται από αρκετούς παράγοντες. Ο αλγόριθμος προσπαθεί να βρει το βέλτιστο μέγεθος εικόνας εξόδου με βάση τη τιμή της ιδιότητας, το μέγεθος της πηγής εικόνας και του πλαισίου εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται η χρήση βήματος 16 ή 32 για ορατό αποτέλεσμα.

--------------------

Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.

Η προεπιλογή είναι **96**.

**Επιστρέφει:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτού του παραμέτρου εξαρτάται από αρκετούς παράγοντες. Ο αλγόριθμος προσπαθεί να βρει το βέλτιστο μέγεθος εικόνας εξόδου με βάση τη τιμή της ιδιότητας, το μέγεθος της πηγής εικόνας και του πλαισίου εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται η χρήση βήματος 16 ή 32 για ορατό αποτέλεσμα.

--------------------

Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.

Η προεπιλογή είναι **96**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Αληθές για τη σχεδίαση μαύρου περιγράμματος γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Αληθές για τη σχεδίαση μαύρου περιγράμματος γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας.

Τιμή: Το χρώμα του διαφανούς τμήματος της εικόνας.

**Επιστρέφει:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public  abstract  void  setImageTransparentColor(Color value)
```

Αποκτά ή ορίζει το διαφανές χρώμα της εικόνας.

Τιμή: Το χρώμα του διαφανούς τμήματος της εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν είναι αληθές.

**Επιστρέφει:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν είναι αληθές.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο-ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean .

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
public abstract void setIncludeOleData(boolean value)
```

Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean .

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