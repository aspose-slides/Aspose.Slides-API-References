---
title: PdfOptions
second_title: Aspose.Sildes για PHP μέσω αναφοράς Java API
description: 
type: docs

url: /el/aspose.slides/pdfoptions/
---
## PdfOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Pdf.
 
### PdfOptions {#PdfOptions}

| Name | Description |
| --- | --- |
| PdfOptions() | Προεπιλεγμένη λειτουργία. |

**Επιστρέφει:**
PdfOptions


---


### getAccessPermissions {#getAccessPermissions}

| Name | Description |
| --- | --- |
| getAccessPermissions () | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιές άδειες πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε το PdfAccessPermissions. |

**Επιστρέφει:**
int


---


### getAdditionalCommonFontFamilies {#getAdditionalCommonFontFamilies}

| Name | Description |
| --- | --- |
| getAdditionalCommonFontFamilies () | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών ορισμένα από τον χρήστη, τις οποίες το Aspose.Slides πρέπει να θεωρεί κοινές. Ανάγνωση/εγγραφή String[]. |

**Επιστρέφει:**
String


---


### getApplyImageTransparent {#getApplyImageTransparent}

| Name | Description |
| --- | --- |
| getApplyImageTransparent () | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν η τιμή είναι true. |

**Επιστρέφει:**
boolean


---


### getBestImagesCompressionRatio {#getBestImagesCompressionRatio}

| Name | Description |
| --- | --- |
| getBestImagesCompressionRatio () | Καθορίζει εάν η πιο αποτελεσματική συμπίεση (αντί για την προεπιλεγμένη) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου εγγράφου PDF. Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και καταναλώνει επιπλέον μνήμη RAM, ενώ αυτή η επιλογή είναι false εξ ορισμού. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean


---


### getCompliance {#getCompliance}

| Name | Description |
| --- | --- |
| getCompliance () | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. Ανάγνωση/εγγραφή PdfCompliance. Η προεπιλογή είναι PdfCompliance#Pdf17. |

**Επιστρέφει:**
int


---


### getDrawSlidesFrame {#getDrawSlidesFrame}

| Name | Description |
| --- | --- |
| getDrawSlidesFrame () | True για να σχεδιάζεται μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean


---


### getEmbedFullFonts {#getEmbedFullFonts}

| Name | Description |
| --- | --- |
| getEmbedFullFonts () | Καθορίζει εάν όλοι οι χαρακτήρες της γραμματοσειράς θα ενσωματωθούν ή μόνο ένα υποσύνολο. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean


---


### getEmbedTrueTypeFontsForASCII {#getEmbedTrueTypeFontsForASCII}

| Name | Description |
| --- | --- |
| getEmbedTrueTypeFontsForASCII () | Καθορίζει εάν το Aspose.Slides θα ενσωματώνει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). Οι γραμματοσειρές για κωδικούς χαρακτήρων άνω του 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές του PDF και επιπλέον γραμματοσειρές που ορίζονται από τον χρήστη. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι true. |

**Επιστρέφει:**
boolean


---


### getImageTransparentColor {#getImageTransparentColor}

| Name | Description |
| --- | --- |
| getImageTransparentColor () | Ανακτά ή ορίζει το διαφανές χρώμα της εικόνας. Τιμή: Το χρώμα διαφάνειας της εικόνας. |

**Επιστρέφει:**
Color


---


### getIncludeOleData {#getIncludeOleData}

| Name | Description |
| --- | --- |
| getIncludeOleData () | True για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean


---


### getInkOptions {#getInkOptions}

| Name | Description |
| --- | --- |
| getInkOptions () | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαχθέν έγγραφο. Μόνο ανάγνωση IInkOptions |

**Επιστρέφει:**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Name | Description |
| --- | --- |
| getJpegQuality () | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG στο έγγραφο PDF. Ανάγνωση/εγγραφή byte. Έχει αποτέλεσμα μόνο όταν το έγγραφο περιέχει εικόνες JPEG. Χρησιμοποιήστε αυτήν τη ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο όταν αποθηκεύετε σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση. Η προεπιλεγμένη τιμή είναι 100. |

**Επιστρέφει:**
byte


---


### getPassword {#getPassword}

| Name | Description |
| --- | --- |
| getPassword () | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String


---


### getRasterizeUnsupportedFontStyles {#getRasterizeUnsupportedFontStyles}

| Name | Description |
| --- | --- |
| getRasterizeUnsupportedFontStyles () | Καθορίζει εάν το κείμενο πρέπει να rasterize ως bitmap και να αποθηκευτεί στο PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean


---


### getSaveMetafilesAsPng {#getSaveMetafilesAsPng}

| Name | Description |
| --- | --- |
| getSaveMetafilesAsPng () | True για τη μετατροπή όλων των metafiles που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι true. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Εάν το SaveMetafilesAsPng οριστεί σε true, η πηγή Metafile μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Εάν οριστεί σε false, η πηγή Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, μπορεί να υπάρξει απώλεια ποιότητας κατά την κλιμάκωση του παραγόμενου εγγράφου. Εάν το Metafile μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να προκύψουν προβλήματα απόδοσης στο εργαλείο προβολής PDF. |

**Επιστρέφει:**
boolean


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides () | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| getSlidesLayoutOptions () | Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

**Επιστρέφει:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### getSufficientResolution {#getSufficientResolution}

| Name | Description |
| --- | --- |
| getSufficientResolution () | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. Ανάγνωση/εγγραφή float. Τιμή: Η επίδραση αυτού του παραμέτρου εξαρτάται από μερικούς παράγοντες. Ο αλγόριθμος προσπαθεί να επιτύχει το βέλτιστο μέγεθος εξαγόμενης εικόνας σύμφωνα με την τιμή της ιδιότητας, το μέγεθος της πηγής εικόνας και το μέγεθος του πλαισίου εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται η χρήση βήματος 16 ή 32 για ορατή επίδραση. Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα εικόνας. Η προεπιλεγμένη τιμή είναι 96. |

**Επιστρέφει:**
float


---


### getTextCompression {#getTextCompression}

| Name | Description |
| --- | --- |
| getTextCompression () | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Ανάγνωση/εγγραφή PdfTextCompression. Η προεπιλογή είναι PdfTextCompression#Flate. |

**Επιστρέφει:**
int


---


### setAccessPermissions {#setAccessPermissions}

| Name | Description |
| --- | --- |
| setAccessPermissions (int) | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιές άδειες πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε το PdfAccessPermissions. |

**Επιστρέφει:**
void


---


### setAdditionalCommonFontFamilies {#setAdditionalCommonFontFamilies}

| Name | Description |
| --- | --- |
| setAdditionalCommonFontFamilies (java.lang.String[]) | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών ορισμένα από τον χρήστη, τις οποίες το Aspose.Slides πρέπει να θεωρεί κοινές. Ανάγνωση/εγγραφή String[]. |

**Επιστρέφει:**
void


---


### setApplyImageTransparent {#setApplyImageTransparent}

| Name | Description |
| --- | --- |
| setApplyImageTransparent (boolean) | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν η τιμή είναι true. |

**Επιστρέφει:**
void


---


### setBestImagesCompressionRatio {#setBestImagesCompressionRatio}

| Name | Description |
| --- | --- |
| setBestImagesCompressionRatio (boolean) | Καθορίζει εάν η πιο αποτελεσματική συμπίεση (αντί για την προεπιλεγμένη) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. Εάν οριστεί σε true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου εγγράφου PDF. Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και καταναλώνει επιπλέον μνήμη RAM, ενώ αυτή η επιλογή είναι false εξ ορισμού. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void


---


### setCompliance {#setCompliance}

| Name | Description |
| --- | --- |
| setCompliance (int) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. Ανάγνωση/εγγραφή PdfCompliance. Η προεπιλογή είναι PdfCompliance#Pdf17. |

**Επιστρέφει:**
void


---


### setDrawSlidesFrame {#setDrawSlidesFrame}

| Name | Description |
| --- | --- |
| setDrawSlidesFrame (boolean) | True για να σχεδιάζεται μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void


---


### setEmbedFullFonts {#setEmbedFullFonts}

| Name | Description |
| --- | --- |
| setEmbedFullFonts (boolean) | Καθορίζει εάν όλοι οι χαρακτήρες της γραμματοσειράς θα ενσωματωθούν ή μόνο ένα υποσύνολο. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void


---


### setEmbedTrueTypeFontsForASCII {#setEmbedTrueTypeFontsForASCII}

| Name | Description |
| --- | --- |
| setEmbedTrueTypeFontsForASCII (boolean) | Καθορίζει εάν το Aspose.Slides θα ενσωματώνει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδικών 33..127). Οι γραμματοσειρές για κωδικούς χαρακτήρων άνω του 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές του PDF και επιπλέον γραμματοσειρές που ορίζονται από τον χρήστη. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι true. |

**Επιστρέφει:**
void


---


### setImageTransparentColor {#setImageTransparentColor}

| Name | Description |
| --- | --- |
| setImageTransparentColor (Color) | Ανακτά ή ορίζει το διαφανές χρώμα της εικόνας. Τιμή: Το χρώμα διαφάνειας της εικόνας. |

**Επιστρέφει:**
void


---


### setIncludeOleData {#setIncludeOleData}

| Name | Description |
| --- | --- |
| setIncludeOleData (boolean) | True για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void


---


### setJpegQuality {#setJpegQuality}

| Name | Description |
| --- | --- |
| setJpegQuality (byte) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG στο έγγραφο PDF. Ανάγνωση/εγγραφή byte. Έχει αποτέλεσμα μόνο όταν το έγγραφο περιέχει εικόνες JPEG. Χρησιμοποιήστε αυτήν τη ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε ένα έγγραφο όταν αποθηκεύετε σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει χειρότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει καλύτερη ποιότητα αλλά ελάχιστη συμπίεση. Η προεπιλεγμένη τιμή είναι 100. |

**Επιστρέφει:**
void


---


### setPassword {#setPassword}

| Name | Description |
| --- | --- |
| setPassword (String) | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void


---


### setRasterizeUnsupportedFontStyles {#setRasterizeUnsupportedFontStyles}

| Name | Description |
| --- | --- |
| setRasterizeUnsupportedFontStyles (boolean) | Καθορίζει εάν το κείμενο πρέπει να rasterize ως bitmap και να αποθηκευτεί στο PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void


---


### setSaveMetafilesAsPng {#setSaveMetafilesAsPng}

| Name | Description |
| --- | --- |
| setSaveMetafilesAsPng (boolean) | True για τη μετατροπή όλων των metafiles που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι true. Το έγγραφο PDF μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Εάν το SaveMetafilesAsPng οριστεί σε true, η πηγή Metafile μετατρέπεται σε μορφή PNG και αποθηκεύεται στο PDF ως ραστερ εικόνα. Εάν οριστεί σε false, η πηγή Metafile μετατρέπεται σε διανυσματικά γραφικά PDF. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, μπορεί να υπάρξει απώλεια ποιότητας κατά την κλιμάκωση του παραγόμενου εγγράφου. Εάν το Metafile μετατραπεί σε διανυσματικά γραφικά PDF, μπορεί να προκύψουν προβλήματα απόδοσης στο εργαλείο προβολής PDF. |

**Επιστρέφει:**
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Name | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

**Επιστρέφει:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

**Επιστρέφει:**
void


---


### setSufficientResolution {#setSufficientResolution}

| Name | Description |
| --- | --- |
| setSufficientResolution (float) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. Ανάγνωση/εγγραφή float. Τιμή: Η επίδραση αυτού του παραμέτρου εξαρτάται από μερικούς παράγοντες. Ο αλγόριθμος προσπαθεί να επιτύχει το βέλτιστο μέγεθος εξαγόμενης εικόνας σύμφωνα με την τιμή της ιδιότητας, το μέγεθος της πηγής εικόνας και το μέγεθος του πλαισίου εικόνας. Η χρήση παρόμοιων τιμών ιδιοτήτων μπορεί να δώσει το ίδιο αποτέλεσμα. Συνιστάται η χρήση βήματος 16 ή 32 για ορατή επίδραση. Η ιδιότητα επηρεάζει το μέγεθος του αρχείου, το χρόνο εξαγωγής και την ποιότητα εικόνας. Η προεπιλεγμένη τιμή είναι 96. |

**Επιστρέφει:**
void


---


### setTextCompression {#setTextCompression}

| Name | Description |
| --- | --- |
| setTextCompression (int) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Ανάγνωση/εγγραφή PdfTextCompression. Η προεπιλογή είναι PdfTextCompression#Flate. |

**Επιστρέφει:**
void


---