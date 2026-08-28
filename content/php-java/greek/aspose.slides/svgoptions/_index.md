---
title: SVGOptions
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs

url: /el/aspose.slides/svgoptions/
---
## SVGOptions κλάση

 Represents an SVG options.
 
### SVGOptions {#SVGOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| SVGOptions() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SVGOptions. |

 **Επιστρέφει:**
SVGOptions


---


### SVGOptions {#SVGOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| SVGOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SVGOptions, καθορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | Η αναφορά του ελεγκτή ενσωμάτωσης συνδέσμων. Ο ελεγκτής ενσωμάτωσης συνδέσμων είναι ένα αντικείμενο delegate που είναι υπεύθυνο για τη λήψη αποφάσεων εάν οι πόροι (όπως εικόνες) πρέπει να ενσωματωθούν ή να αναφερθούν ως εξωτερικοί πόροι. |

 **Επιστρέφει:**
SVGOptions


---


### getDefault {#getDefault}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefault () | Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. Μόνο για ανάγνωση SVGOptions. |

 **Επιστρέφει:**
SVGOptions


---


### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| Όνομα | Περιγραφή |
| --- | --- |
| getDeletePicturesCroppedAreas () | Μια σημαία boolean υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα μέρη θα αφαιρεθούν, εάν false θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο) |

 **Επιστρέφει:**
boolean


---


### getDisable3DText {#getDisable3DText}

| Όνομα | Περιγραφή |
| --- | --- |
| getDisable3DText () | Καθορίζει εάν το κείμενο 3D είναι απενεργοποιημένο στο SVG. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### getDisableFontLigatures {#getDisableFontLigatures}

| Όνομα | Περιγραφή |
| --- | --- |
| getDisableFontLigatures () | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λυσηγμάτων. Όταν οριστεί σε true, τα λυσήματα θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι false. |

 **Επιστρέφει:**
boolean


---


### getDisableGradientSplit {#getDisableGradientSplit}

| Όνομα | Περιγραφή |
| --- | --- |
| getDisableGradientSplit () | Απενεργοποιεί τον διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### getDisableLineEndCropping {#getDisableLineEndCropping}

| Όνομα | Περιγραφή |
| --- | --- |
| getDisableLineEndCropping () | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού ενθέσεων για τους δείκτες. Η μηχανή εγγραφής SVG του Aspose.Slides διαθέτει λύση: κόβει το άκρο της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### getExternalFontsHandling {#getExternalFontsHandling}

| Όνομα | Περιγραφή |
| --- | --- |
| getExternalFontsHandling () | Καθορίζει τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/Εγγραφή SvgExternalFontsHandling. |

 **Επιστρέφει:**
int


---


### getInkOptions {#getInkOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| getInkOptions () | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση IInkOptions |

 **Επιστρέφει:**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Όνομα | Περιγραφή |
| --- | --- |
| getJpegQuality () | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/Εγγραφή int. |

 **Επιστρέφει:**
int


---


### getMetafileRasterizationDpi {#getMetafileRasterizationDpi}

| Όνομα | Περιγραφή |
| --- | --- |
| getMetafileRasterizationDpi () | Επιστρέφει ή ορίζει το χαμηλότερο όριο ανάλυσης για rasterization μετααρχείου. Ανάγνωση/Εγγραφή int. |

 **Επιστρέφει:**
int


---


### getPicturesCompression {#getPicturesCompression}

| Όνομα | Περιγραφή |
| --- | --- |
| getPicturesCompression () | Αντιπροσωπεύει το επίπεδο συμπίεσης των εικόνων |

 **Επιστρέφει:**
int


---


### getShapeFormattingController {#getShapeFormattingController}

| Όνομα | Περιγραφή |
| --- | --- |
| getShapeFormattingController () | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/Εγγραφή ISvgShapeFormattingController. |

 **Επιστρέφει:**
[VideoPlayerHtmlController](../videoplayerhtmlcontroller)


---


### getSimple {#getSimple}

| Όνομα | Περιγραφή |
| --- | --- |
| getSimple () | Επιστρέφει ρυθμίσεις για τη δημιουργία του πιο απλού και μικρότερου αρχείου SVG. Μόνο για ανάγνωση SVGOptions. |

 **Επιστρέφει:**
SVGOptions


---


### getUseFrameRotation {#getUseFrameRotation}

| Όνομα | Περιγραφή |
| --- | --- |
| getUseFrameRotation () | Καθορίζει αν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/Εγγραφή boolean. Η προεπιλεγμένη τιμή είναι true. |

 **Επιστρέφει:**
boolean


---


### getUseFrameSize {#getUseFrameSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getUseFrameSize () | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί στην περιοχή απόδοσης ή όχι. Ανάγνωση/Εγγραφή boolean. Η προεπιλεγμένη τιμή είναι false. |

 **Επιστρέφει:**
boolean


---


### getVectorizeText {#getVectorizeText}

| Όνομα | Περιγραφή |
| --- | --- |
| getVectorizeText () | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### getWYSIWYG {#getWYSIWYG}

| Όνομα | Περιγραφή |
| --- | --- |
| getWYSIWYG () | Επιστρέφει ρυθμίσεις για τη δημιουργία του πιο ακριβούς αρχείου SVG. Μόνο για ανάγνωση SVGOptions. |

 **Επιστρέφει:**
SVGOptions


---


### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| Όνομα | Περιγραφή |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | Μια σημαία boolean υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν true, τα περικομμένα μέρη θα αφαιρεθούν, εάν false θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο) |

 **Επιστρέφει:**
void


---


### setDisable3DText {#setDisable3DText}

| Όνομα | Περιγραφή |
| --- | --- |
| setDisable3DText (boolean) | Καθορίζει εάν το κείμενο 3D είναι απενεργοποιημένο στο SVG. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setDisableFontLigatures {#setDisableFontLigatures}

| Όνομα | Περιγραφή |
| --- | --- |
| setDisableFontLigatures (boolean) | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λυσηγμάτων. Όταν οριστεί σε true, τα λυσήματα θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι false. |

 **Επιστρέφει:**
void


---


### setDisableGradientSplit {#setDisableGradientSplit}

| Όνομα | Περιγραφή |
| --- | --- |
| setDisableGradientSplit (boolean) | Απενεργοποιεί τον διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setDisableLineEndCropping {#setDisableLineEndCropping}

| Όνομα | Περιγραφή |
| --- | --- |
| setDisableLineEndCropping (boolean) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού ενθέσεων για τους δείκτες. Η μηχανή εγγραφής SVG του Aspose.Slides διαθέτει λύση: κόβει το άκρο της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setExternalFontsHandling {#setExternalFontsHandling}

| Όνομα | Περιγραφή |
| --- | --- |
| setExternalFontsHandling (int) | Καθορίζει τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/Εγγραφή SvgExternalFontsHandling. |

 **Επιστρέφει:**
void


---


### setJpegQuality {#setJpegQuality}

| Όνομα | Περιγραφή |
| --- | --- |
| setJpegQuality (int) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/Εγγραφή int. |

 **Επιστρέφει:**
void


---


### setMetafileRasterizationDpi {#setMetafileRasterizationDpi}

| Όνομα | Περιγραφή |
| --- | --- |
| setMetafileRasterizationDpi (int) | Επιστρέφει ή ορίζει το χαμηλότερο όριο ανάλυσης για rasterization μετααρχείου. Ανάγνωση/Εγγραφή int. |

 **Επιστρέφει:**
void


---


### setPicturesCompression {#setPicturesCompression}

| Όνομα | Περιγραφή |
| --- | --- |
| setPicturesCompression (int) | Αντιπροσωπεύει το επίπεδο συμπίεσης των εικόνων |

 **Επιστρέφει:**
void


---


### setShapeFormattingController {#setShapeFormattingController}

| Όνομα | Περιγραφή |
| --- | --- |
| setShapeFormattingController ([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/Εγγραφή ISvgShapeFormattingController. |

 **Επιστρέφει:**
void


---


### setUseFrameRotation {#setUseFrameRotation}

| Όνομα | Περιγραφή |
| --- | --- |
| setUseFrameRotation (boolean) | Καθορίζει αν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/Εγγραφή boolean. Η προεπιλεγμένη τιμή είναι true. |

 **Επιστρέφει:**
void


---


### setUseFrameSize {#setUseFrameSize}

| Όνομα | Περιγραφή |
| --- | --- |
| setUseFrameSize (boolean) | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί στην περιοχή απόδοσης ή όχι. Ανάγνωση/Εγγραφή boolean. Η προεπιλεγμένη τιμή είναι false. |

 **Επιστρέφει:**
void


---


### setVectorizeText {#setVectorizeText}

| Όνομα | Περιγραφή |
| --- | --- |
| setVectorizeText (boolean) | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---