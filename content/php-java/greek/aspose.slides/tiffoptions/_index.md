---
title: TiffOptions
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/tiffoptions/
---
## TiffOptions κλάση

 Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.
 
### TiffOptions {#TiffOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| TiffOptions() | Προεπιλεγμένη λειτουργία. |

 **Επιστρέφει:**
TiffOptions


---


### getBwConversionMode {#getBwConversionMode}

| Όνομα | Περιγραφή |
| --- | --- |
| getBwConversionMode () | Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν το CompressionType( #getCompressionType/ #setCompressionType(int)) έχει οριστεί σε TiffCompressionTypes#CCITT4 ή TiffCompressionTypes#CCITT3 Ανάγνωση/εγγραφή BlackWhiteConversionMode. Η προεπιλογή είναι BlackWhiteConversionMode#Default. |

 **Επιστρέφει:**
int


---


### getCompressionType {#getCompressionType}

| Όνομα | Περιγραφή |
| --- | --- |
| getCompressionType () | Καθορίζει τον τύπο συμπίεσης. Ανάγνωση/εγγραφή TiffCompressionTypes. |

 **Επιστρέφει:**
int


---


### getDpiX {#getDpiX}

| Όνομα | Περιγραφή |
| --- | --- |
| getDpiX () | Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long. |

 **Επιστρέφει:**
long


---


### getDpiY {#getDpiY}

| Όνομα | Περιγραφή |
| --- | --- |
| getDpiY () | Καθορίζει την κατακόρυφη ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long. |

 **Επιστρέφει:**
long


---


### getImageSize {#getImageSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getImageSize () | Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογιστούν βάσει της τιμής μεγέθους διαφάνειας της παρουσίασης. Ανάγνωση/εγγραφή java.awt.Dimension. |

 **Επιστρέφει:**
Dimension


---


### getInkOptions {#getInkOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| getInkOptions () | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink σε εξαγόμενο έγγραφο. Μόνο για ανάγνωση IInkOptions |

 **Επιστρέφει:**
[InkOptions](../inkoptions)


---


### getPixelFormat {#getPixelFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getPixelFormat () | Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες. Ανάγνωση/εγγραφή ImagePixelFormat. |

 **Επιστρέφει:**
int


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowHiddenSlides () | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false. |

 **Επιστρέφει:**
boolean


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlidesLayoutOptions () | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

 **Επιστρέφει:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### setBwConversionMode {#setBwConversionMode}

| Όνομα | Περιγραφή |
| --- | --- |
| setBwConversionMode (int) | Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν το CompressionType( #getCompressionType/ #setCompressionType(int)) έχει οριστεί σε TiffCompressionTypes#CCITT4 ή TiffCompressionTypes#CCITT3 Ανάγνωση/εγγραφή BlackWhiteConversionMode. Η προεπιλογή είναι BlackWhiteConversionMode#Default. |

 **Επιστρέφει:**
void


---


### setCompressionType {#setCompressionType}

| Όνομα | Περιγραφή |
| --- | --- |
| setCompressionType (int) | Καθορίζει τον τύπο συμπίεσης. Ανάγνωση/εγγραφή TiffCompressionTypes. |

 **Επιστρέφει:**
void


---


### setDpiX {#setDpiX}

| Όνομα | Περιγραφή |
| --- | --- |
| setDpiX (long) | Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long. |

 **Επιστρέφει:**
void


---


### setDpiY {#setDpiY}

| Όνομα | Περιγραφή |
| --- | --- |
| setDpiY (long) | Καθορίζει την κατακόρυφη ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή long. |

 **Επιστρέφει:**
void


---


### setImageSize {#setImageSize}

| Όνομα | Περιγραφή |
| --- | --- |
| setImageSize (Dimension) | Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογιστούν βάσει της τιμής μεγέθους διαφάνειας της παρουσίασης. Ανάγνωση/εγγραφή java.awt.Dimension. |

 **Επιστρέφει:**
void


---


### setPixelFormat {#setPixelFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setPixelFormat (int) | Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες. Ανάγνωση/εγγραφή ImagePixelFormat. |

 **Επιστρέφει:**
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowHiddenSlides (boolean) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false. |

 **Επιστρέφει:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

 **Επιστρέφει:**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. |

 **Επιστρέφει:**
void


---