---
title: MarkdownSaveOptions
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/markdownsaveoptions/
---
## MarkdownSaveOptions κατηγορία

Αναπαριστά τις επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.

### MarkdownSaveOptions {#MarkdownSaveOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| MarkdownSaveOptions() | Ctor. |

**Επιστρέφει:**
MarkdownSaveOptions

---

### getBasePath {#getBasePath}

| Όνομα | Περιγραφή |
| --- | --- |
| getBasePath () | Καθορίζει τη βασική διαδρομή όπου το έγγραφο με τους πόρους θα αποθηκευτεί. Η προεπιλογή είναι ο τρέχων φάκελος της εφαρμογής. |

**Επιστρέφει:**
String

---

### getExportType {#getExportType}

| Όνομα | Περιγραφή |
| --- | --- |
| getExportType () | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι TextOnly. |

**Επιστρέφει:**
int

---

### getFlavor {#getFlavor}

| Όνομα | Περιγραφή |
| --- | --- |
| getFlavor () | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι Multi-markdown. |

**Επιστρέφει:**
int

---

### getHandleRepeatedSpaces {#getHandleRepeatedSpaces}

| Όνομα | Περιγραφή |
| --- | --- |
| getHandleRepeatedSpaces () | Καθορίζει πώς θα αντιμετωπίζονται τα επαναλαμβανόμενα κανονικά διαστήματα κατά την εξαγωγή σε Markdown. Η ιδιότητα αυτή ορίζει αν τα διαδοχικά κενά είναι: - διατηρημένα ως κανονικά διαστήματα, - εναλλασσόμενα μεταξύ κανονικών διαστημάτων και οντοτήτων non-breaking space (&nbsp;), - ή πλήρως αντικατεστημένα (αfter το πρώτο) με non-breaking space για να διατηρηθεί η οπτική στοίχιση στην έξοδο Markdown. Η προεπιλεγμένη τιμή είναι HandleRepeatedSpaces#AlternateSpacesToNbsp. |

**Επιστρέφει:**
int

---

### getImagesSaveFolderName {#getImagesSaveFolderName}

| Όνομα | Περιγραφή |
| --- | --- |
| getImagesSaveFolderName () | Καθορίζει το όνομα φακέλου όπου θα αποθηκευτούν οι εικόνες. Η προεπιλογή είναι Images. |

**Επιστρέφει:**
String

---

### getNewLineType {#getNewLineType}

| Όνομα | Περιγραφή |
| --- | --- |
| getNewLineType () | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows). Η προεπιλογή είναι Unix. |

**Επιστρέφει:**
int

---

### getRemoveEmptyLines {#getRemoveEmptyLines}

| Όνομα | Περιγραφή |
| --- | --- |
| getRemoveEmptyLines () | Εάν οριστεί σε true, αφαιρεί κενές ή μόνο διαστήματα γραμμές από το τελικό έξοδο Markdown. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean

---

### getShowComments {#getShowComments}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowComments () | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean

---

### getShowHiddenSlides {#getShowHiddenSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowHiddenSlides () | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean

---

### getShowSlideNumber {#getShowSlideNumber}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowSlideNumber () | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean

---

### getSlideNumberFormat {#getSlideNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlideNumberFormat () | Λαμβάνει ή ορίζει τη συμβολοσειρά μορφοποίησης που χρησιμοποιείται για τις επικεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το σύμβολο κράτησης θέσης "{0}", το οποίο θα αντικατασταθεί με τον δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: "# Slide {0}" θα παραγάγει "# Slide 1", "# Slide 2", κ.λπ. |

**Επιστρέφει:**
String

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentException | Επιδίωξη εάν η συμβολοσειρά μορφοποίησης δεν περιέχει το σύμβολο κράτησης θέσης "{0}". |

---

### setBasePath {#setBasePath}

| Όνομα | Περιγραφή |
| --- | --- |
| setBasePath (String) | Καθορίζει τη βασική διαδρομή όπου το έγγραφο με τους πόρους θα αποθηκευτεί. Η προεπιλογή είναι ο τρέχων φάκελος της εφαρμογής. |

**Επιστρέφει:**
void

---

### setExportType {#setExportType}

| Όνομα | Περιγραφή |
| --- | --- |
| setExportType (int) | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι TextOnly. |

**Επιστρέφει:**
void

---

### setFlavor {#setFlavor}

| Όνομα | Περιγραφή |
| --- | --- |
| setFlavor (int) | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι Multi-markdown. |

**Επιστρέφει:**
void

---

### setHandleRepeatedSpaces {#setHandleRepeatedSpaces}

| Όνομα | Περιγραφή |
| --- | --- |
| setHandleRepeatedSpaces (int) | Καθορίζει πώς θα αντιμετωπίζονται τα επαναλαμβανόμενα κανονικά διαστήματα κατά την εξαγωγή σε Markdown. Η ιδιότητα αυτή ορίζει αν τα διαδοχικά κενά είναι: - διατηρημένα ως κανονικά διαστήματα, - εναλλασσόμενα μεταξύ κανονικών διαστημάτων και οντοτήτων non-breaking space (&nbsp;), - ή πλήρως αντικατεστημένα (αfter το πρώτο) με non-breaking space για να διατηρηθεί η οπτική στοίχιση στην έξοδο Markdown. Η προεπιλεγμένη τιμή είναι HandleRepeatedSpaces#AlternateSpacesToNbsp. |

**Επιστρέφει:**
void

---

### setImageSaving {#setImageSaving}

| Όνομα | Περιγραφή |
| --- | --- |
| setImageSaving ([MarkdownSaveOptions.MarkdownImageSavingHandler](../markdownsaveoptions.markdownimagesavinghandler)) | Συμβαίνει για κάθε μη-SVG εικόνα (bitmap ή metafile) κατά την εξαγωγή σε Markdown. Επιτρέπει την προσαρμογή του τρόπου αποθήκευσης και αναφοράς της εικόνας. Εάν δεν αντιμετωπιστεί, η εικόνα αποθηκεύεται τοπικά με σχετικό σύνδεσμο. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | [MarkdownSaveOptions.MarkdownImageSavingHandler](../markdownsaveoptions.markdownimagesavinghandler) | Συμβάν αποθήκευσης εικόνας Markdown. |

**Επιστρέφει:**
void

---

### setImagesSaveFolderName {#setImagesSaveFolderName}

| Όνομα | Περιγραφή |
| --- | --- |
| setImagesSaveFolderName (String) | Καθορίζει το όνομα φακέλου όπου θα αποθηκευτούν οι εικόνες. Η προεπιλογή είναι Images. |

**Επιστρέφει:**
void

---

### setNewLineType {#setNewLineType}

| Όνομα | Περιγραφή |
| --- | --- |
| setNewLineType (int) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows). Η προεπιλογή είναι Unix. |

**Επιστρέφει:**
void

---

### setRemoveEmptyLines {#setRemoveEmptyLines}

| Όνομα | Περιγραφή |
| --- | --- |
| setRemoveEmptyLines (boolean) | Εάν οριστεί σε true, αφαιρεί κενές ή μόνο διαστήματα γραμμές από το τελικό έξοδο Markdown. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void

---

### setShowComments {#setShowComments}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowComments (boolean) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void

---

### setShowHiddenSlides {#setShowHiddenSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowHiddenSlides (boolean) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void

---

### setShowSlideNumber {#setShowSlideNumber}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowSlideNumber (boolean) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void

---

### setSlideNumberFormat {#setSlideNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setSlideNumberFormat (String) | Λαμβάνει ή ορίζει τη συμβολοσειρά μορφοποίησης που χρησιμοποιείται για τις επικεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το σύμβολο κράτησης θέσης "{0}", το οποίο θα αντικατασταθεί με τον δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: "# Slide {0}" θα παραγάγει "# Slide 1", "# Slide 2", κ.λπ. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentException | Επιδίωξη εάν η συμβολοσειρά μορφοποίησης δεν περιέχει το σύμβολο κράτησης θέσης "{0}". |

---

### setSvgImageSaving {#setSvgImageSaving}

| Όνομα | Περιγραφή |
| --- | --- |
| setSvgImageSaving ([MarkdownSaveOptions.MarkdownSvgImageSavingHandler](../markdownsaveoptions.markdownsvgimagesavinghandler)) | Συμβαίνει για κάθε SVG εικόνα κατά την εξαγωγή σε Markdown. Επιτρέπει την αντικατάσταση της προεπιλεγμένης αποθήκευσης και δημιουργίας συνδέσμου. Εάν δεν αντιμετωπιστεί, το SVG αποθηκεύεται τοπικά με σχετικό σύνδεσμο. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | [MarkdownSaveOptions.MarkdownSvgImageSavingHandler](../markdownsaveoptions.markdownsvgimagesavinghandler) | Συμβάν αποθήκευσης SVG εικόνας Markdown. |

**Επιστρέφει:**
void

---