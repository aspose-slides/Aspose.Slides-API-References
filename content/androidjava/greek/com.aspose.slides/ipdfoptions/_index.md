---
title: IPdfOptions
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Pdf.
type: docs
url: /el/com.aspose.slides/ipdfoptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή Pdf.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. |
| [setTextCompression(int value)](#setTextCompression-int-) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Δείχνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλεγείται αυτόματα. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Δείχνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλεγείται αυτόματα. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True για ενσωμάτωση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True για ενσωμάτωση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών ορισμένων από τον χρήστη που το Aspose.Slides θα πρέπει να θεωρεί κοινές. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών ορισμένων από τον χρήστη που το Aspose.Slides θα πρέπει να θεωρεί κοινές. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Καθορίζει εάν όλα τα γράμματα της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το χρησιμοποιούμενο υποσύνολο. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Καθορίζει εάν όλα τα γράμματα της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το χρησιμοποιούμενο υποσύνολο. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη γραφή. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη γραφή. |
| [getJpegQuality()](#getJpegQuality--) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. |
| [getCompliance()](#getCompliance--) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. |
| [setCompliance(int value)](#setCompliance-int-) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. |
| [getPassword()](#getPassword--) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Ανακτά ή ορίζει το διαυγές χρώμα της εικόνας. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Ανακτά ή ορίζει το διαυγές χρώμα της εικόνας. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Εφαρμόζει το καθορισμένο διαυγές χρώμα σε μια εικόνα εάν είναι true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Εφαρμόζει το καθορισμένο διαυγές χρώμα σε μια εικόνα εάν είναι true. |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getIncludeOleData()](#getIncludeOleData--) | True για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. |

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

Δείχνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλεγείται αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου εγγράφου PDF.

--------------------

Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και χρειάζεται επιπλέον μνήμη RAM, και αυτή η επιλογή έχει προεπιλογή false.

--------------------

Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Δείχνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλεγείται αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου εγγράφου PDF.

--------------------

Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και χρειάζεται επιπλέον μνήμη RAM, και αυτή η επιλογή έχει προεπιλογή false.

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

True για ενσωμάτωση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. Οι γραμματοσειρές για κώδικες χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Επιστρέφει:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True για ενσωμάτωση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. Οι γραμματοσειρές για κώδικες χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα. Ανάγνωση/εγγραφή boolean.

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

Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών ορισμένων από τον χρήστη που το Aspose.Slides θα πρέπει να θεωρεί κοινές. Ανάγνωση/εγγραφή String[].

**Επιστρέφει:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών ορισμένων από τον χρήστη που το Aspose.Slides θα πρέπει να θεωρεί κοινές. Ανάγνωση/εγγραφή String[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Καθορίζει εάν όλα τα γράμματα της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το χρησιμοποιούμενο υποσύνολο. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Καθορίζει εάν όλα τα γράμματα της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το χρησιμοποιούμενο υποσύνολο. Ανάγνωση/εγγραφή boolean.

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

Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη γραφή. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Δείχνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη γραφή. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean.

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

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte.

--------------------
Έχει επίδραση μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει τη χειρότερη ποιότητα αλλά τη μέγιστη συμπίεση και 100 σημαίνει την καλύτερη ποιότητα αλλά τη ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **100**.

**Επιστρέφει:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte.

--------------------
Έχει επίδραση μόνο όταν το έγγραφο περιέχει εικόνες JPEG.

Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει τη χειρότερη ποιότητα αλλά τη μέγιστη συμπίεση και 100 σημαίνει την καλύτερη ποιότητα αλλά τη ελάχιστη συμπίεση.

Η προεπιλεγμένη τιμή είναι **100**.

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

Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

True για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------
Η προεπιλογή είναι **true**. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Εάν το SaveMetafilesAsPng είναι true, τότε η αρχική εικόνα Metafile μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Εάν είναι false, η Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, αν η Metafile μετατραπεί σε PNG, μπορεί να προκύψει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Αν μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να εμφανιστούν προβλήματα απόδοσης στο εργαλείο προβολής PDF.

**Επιστρέφει:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------
Η προεπιλογή είναι **true**. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Εάν το SaveMetafilesAsPng είναι true, τότε η αρχική εικόνα Metafile μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Εάν είναι false, η Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, αν η Metafile μετατραπεί σε PNG, μπορεί να προκύψει απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Αν μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να εμφανιστούν προβλήματα απόδοσης στο εργαλείο προβολής PDF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτού του παραμέτρου εξαρτάται από διάφορους παράγοντες. Ο αλγόριθμος προσπαθεί να επιτύχει το καλύτερο μέγεθος εικόνας εξόδου βάσει της τιμής της ιδιότητας, του μεγέθους της πηγαίας εικόνας και του πλαισίου της εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται η χρήση βήματος 16 ή 32 για ορατό αποτέλεσμα.

--------------------
Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.

Η προεπιλεγμένη τιμή είναι **96**.

**Επιστρέφει:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή float.

Τιμή: Η επίδραση αυτού του παραμέτρου εξαρτάται από διάφορους παράγοντες. Ο αλγόριθμος προσπαθεί να επιτύχει το καλύτερο μέγεθος εικόνας εξόδου βάσει της τιμής της ιδιότητας, του μεγέθους της πηγαίας εικόνας και του πλαισίου της εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται η χρήση βήματος 16 ή 32 για ορατό αποτέλεσμα.

--------------------
Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα της εικόνας.

Η προεπιλεγμένη τιμή είναι **96**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------
Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

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

Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract Integer getImageTransparentColor()
```

Ανακτά ή ορίζει το διαυγές χρώμα της εικόνας.

Τιμή: Το χρώμα του διαυγού χρώματος της εικόνας.

**Επιστρέφει:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Ανακτά ή ορίζει το διαυγές χρώμα της εικόνας.

Τιμή: Το χρώμα του διαυγού χρώματος της εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Εφαρμόζει το καθορισμένο διαυγές χρώμα σε μια εικόνα εάν είναι true.

**Επιστρέφει:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Εφαρμόζει το καθορισμένο διαυγές χρώμα σε μια εικόνα εάν είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. Ανάγνωση/εγγραφή  boolean .

--------------------
> ```
> Παράδειγμα:
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
Η προεπιλογή είναι  **false** .

**Επιστρέφει:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. Ανάγνωση/εγγραφή  boolean .

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
Η προεπιλογή είναι  **false** .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |