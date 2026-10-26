---
title: HtmlOptions
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/htmloptions/
---
## HtmlOptions κλάση

 Αναπαριστά επιλογές εξαγωγής HTML.
 
### HtmlOptions {#HtmlOptions}

| Name | Description |
| --- | --- |
| HtmlOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Δημιουργεί ένα νέο αντικείμενο HtmlOptions ορίζοντας την κλήση επιστροφής. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | Αντικειμενική κλήση επιστροφής που ελέγχει την αποθήκευση του έργου. |

 **Επιστρέφει:**
HtmlOptions


---


### HtmlOptions {#HtmlOptions}

| Name | Description |
| --- | --- |
| HtmlOptions() | Δημιουργεί ένα νέο αντικείμενο HtmlOptions για αποθήκευση σε ένα μόνο αρχείο HTML. |

 **Επιστρέφει:**
HtmlOptions


---


### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| getDeletePicturesCroppedAreas () | Σημαία boolean που υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν false θα σειράριστούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). |

 **Επιστρέφει:**
boolean


---


### getDisableFontLigatures {#getDisableFontLigatures}

| Name | Description |
| --- | --- |
| getDisableFontLigatures () | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση διφθογγίων. Όταν οριστεί σε true, τα διφθόγγια θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι false. |

 **Επιστρέφει:**
boolean


---


### getHtmlFormatter {#getHtmlFormatter}

| Name | Description |
| --- | --- |
| getHtmlFormatter () | Επιστρέφει ή ορίζει το πρότυπο HTML. Ανάγνωση/εγγραφή IHtmlFormatter. |

 **Επιστρέφει:**
[HtmlFormatter](../htmlformatter)


---


### getInkOptions {#getInkOptions}

| Name | Description |
| --- | --- |
| getInkOptions () | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση IInkOptions |

 **Επιστρέφει:**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Name | Description |
| --- | --- |
| getJpegQuality () | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte. Έχει αντίκτυπο μόνο όταν το έγγραφο περιέχει εικόνες JPEG. Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει την χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 την υψηλότερη ποιότητα αλλά ελάχιστη συμπίεση. Η προεπιλεγμένη τιμή είναι 95. |

 **Επιστρέφει:**
byte


---


### getPicturesCompression {#getPicturesCompression}

| Name | Description |
| --- | --- |
| getPicturesCompression () | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |

 **Επιστρέφει:**
int


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides () | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false. |

 **Επιστρέφει:**
boolean


---


### getSlideImageFormat {#getSlideImageFormat}

| Name | Description |
| --- | --- |
| getSlideImageFormat () | Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. Ανάγνωση/εγγραφή ISlideImageFormat. |

 **Επιστρέφει:**
[SlideImageFormat](../slideimageformat)


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| getSlidesLayoutOptions () | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

 **Επιστρέφει:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### getSvgResponsiveLayout {#getSvgResponsiveLayout}

| Name | Description |
| --- | --- |
| getSvgResponsiveLayout () | True για εξαίρεση των χαρακτηριστικών width και height από το κοντέινερ svg – αυτό κάνει τη διάταξη ανταποκρινόμενη. False – διαφορετικά. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | Σημαία boolean που υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν false θα σειράριστούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). |

 **Επιστρέφει:**
void


---


### setDisableFontLigatures {#setDisableFontLigatures}

| Name | Description |
| --- | --- |
| setDisableFontLigatures (boolean) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση διφθογγίων. Όταν οριστεί σε true, τα διφθόγγια θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι false. |

 **Επιστρέφει:**
void


---


### setHtmlFormatter {#setHtmlFormatter}

| Name | Description |
| --- | --- |
| setHtmlFormatter ([HtmlFormatter](../htmlformatter)) | Επιστρέφει ή ορίζει το πρότυπο HTML. Ανάγνωση/εγγραφή IHtmlFormatter. |

 **Επιστρέφει:**
void


---


### setJpegQuality {#setJpegQuality}

| Name | Description |
| --- | --- |
| setJpegQuality (byte) | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα σε έγγραφο PDF. Ανάγνωση/εγγραφή byte. Έχει αντίκτυπο μόνο όταν το έγγραφο περιέχει εικόνες JPEG. Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των εικόνων μέσα σε έγγραφο κατά την αποθήκευση σε μορφή PDF. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει τη χαμηλότερη ποιότητα αλλά μέγιστη συμπίεση και 100 τη βέλτιστη ποιότητα αλλά ελάχιστη συμπίεση. Η προεπιλεγμένη τιμή είναι 95. |

 **Επιστρέφει:**
void


---


### setPicturesCompression {#setPicturesCompression}

| Name | Description |
| --- | --- |
| setPicturesCompression (int) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |

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


### setSlideImageFormat {#setSlideImageFormat}

| Name | Description |
| --- | --- |
| setSlideImageFormat ([SlideImageFormat](../slideimageformat)) | Επιστρέφει ή ορίζει τις επιλογές μορφής εικόνας διαφάνειας. Ανάγνωση/εγγραφή ISlideImageFormat. |

 **Επιστρέφει:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

 **Επιστρέφει:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

 **Επιστρέφει:**
void


---


### setSvgResponsiveLayout {#setSvgResponsiveLayout}

| Name | Description |
| --- | --- |
| setSvgResponsiveLayout (boolean) | True για εξαίρεση των χαρακτηριστικών width και height από το κοντέινερ svg – αυτό κάνει τη διάταξη ανταποκρινόμενη. False – διαφορετικά. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
void


---