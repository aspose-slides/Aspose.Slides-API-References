---
title: Slide
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/slide/
---
## Slide κλάση

  Αντιπροσωπεύει μια διαφάνεια σε μια παρουσίαση.
 
### getHeaderFooterManager {#getHeaderFooterManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeaderFooterManager () | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. Μόνο για ανάγνωση ISlideHeaderFooterManager. |

 ****Επιστρέφει:****
[SlideHeaderFooterManager](../slideheaderfootermanager)


---


### getHidden {#getHidden}

| Όνομα | Περιγραφή |
| --- | --- |
| getHidden () | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια μιας παρουσίασης διαφανειών. Ανάγνωση/εγγραφή boolean. |

 ****Επιστρέφει:****
boolean


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage (float, float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

 ****Επιστρέφει:****
IImage


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage () | Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους). |

 ****Επιστρέφει:****
IImage


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage (Dimension) | Επιστρέφει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

 ****Επιστρέφει:****
IImage


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage ([TiffOptions](../tiffoptions)) | Επιστρέφει ένα αντικείμενο Thumbnail tiff image με καθορισμένες παραμέτρους. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [TiffOptions](../tiffoptions) | Επιλογές tiff. |

 ****Επιστρέφει:****
IImage

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Εκκρίνεται όταν options.SlideLayoutOption είναι NotesCommentsLayoutingOptions και η ιδιότητα NotesPosition παίρνει την τιμή NotesPositions.BottomFull. |


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions)) | Επιστρέφει ένα αντικείμενο Thumbnail Image. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές απόδοσης. |

 ****Επιστρέφει:****
IImage

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Εκκρίνεται όταν notesCommentsLayouting.NotesPosition παίρνει την τιμή NotesPositions.BottomFull |
 


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions), float, float) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές απόδοσης. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

 ****Επιστρέφει:****
IImage

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Εκκρίνεται όταν notesCommentsLayouting.NotesPosition παίρνει την τιμή NotesPositions.BottomFull |
 


---


### getImage {#getImage}

| Όνομα | Περιγραφή |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions), Dimension) | Επιστέψει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές απόδοσης. |
| imageSize | Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

 ****Επιστρέφει:****
IImage

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Εκκρίνεται όταν options.SlideLayoutOption είναι NotesCommentsLayoutingOptions και η ιδιότητα NotesPosition παίρνει την τιμή NotesPositions.BottomFull. |
 


---


### getLayoutSlide {#getLayoutSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getLayoutSlide () | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. Ανάγνωση/εγγραφή ILayoutSlide. |

 ****Επιστρέφει:****
[LayoutSlide](../layoutslide)


---


### getNotesSlideManager {#getNotesSlideManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getNotesSlideManager () | Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και αφαίρεσή της. Μόνο για ανάγνωση INotesSlideManager. |

 ****Επιστρέφει:****
[NotesSlideManager](../notesslidemanager)


---


### getShowMasterShapes {#getShowMasterShapes}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowMasterShapes () | Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean. |

 ****Επιστρέφει:****
boolean


---


### getSlideComments {#getSlideComments}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlideComments ([CommentAuthor](../commentauthor)) | Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | Συγγραφέας των σχολίων προς εύρεση ή null για επιστροφή όλων των σχολίων. |

 ****Επιστρέφει:****
[Comment](../comment), [ModernComment](../moderncomment)


---


### getSlideNumber {#getSlideNumber}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlideNumber () | Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή Presentation#getSlides είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/εγγραφή int. |

 ****Επιστρέφει:****
int


---


### getThemeManager {#getThemeManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getThemeManager () | Επιστρέφει τον αντικαταστάτη διαχειριστή θέματος. Μόνο για ανάγνωση IOverrideThemeManager. |

 ****Επιστρέφει:****
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Όνομα | Περιγραφή |
| --- | --- |
| joinPortionsWithSameFormatting () | Συνδέει τμήματα με ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |

 ****Επιστρέφει:****
void


---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove () | Αφαιρεί τη διαφάνεια από την παρουσίαση. |

 ****Επιστρέφει:****
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | PptxEditException | Εκκρίνεται εάν η διαφάνεια έχει ήδη αφαιρεθεί από την παρουσίαση. |


---


### reset {#reset}

| Όνομα | Περιγραφή |
| --- | --- |
| reset () | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στη LayoutSlide. |

 ****Επιστρέφει:****
void


---


### setHidden {#setHidden}

| Όνομα | Περιγραφή |
| --- | --- |
| setHidden (boolean) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια μιας παρουσίασης διαφανειών. Ανάγνωση/εγγραφή boolean. |

 ****Επιστρέφει:****
void


---


### setLayoutSlide {#setLayoutSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| setLayoutSlide ([LayoutSlide](../layoutslide)) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. Ανάγνωση/εγγραφή ILayoutSlide. |

 ****Επιστρέφει:****
void


---


### setShowMasterShapes {#setShowMasterShapes}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowMasterShapes (boolean) | Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean. |

 ****Επιστρέφει:****
void


---


### setSlideNumber {#setSlideNumber}

| Όνομα | Περιγραφή |
| --- | --- |
| setSlideNumber (int) | Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή Presentation#getSlides είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/εγγραφή int. |

 ****Επιστρέφει:****
void


---


### writeAsEmf {#writeAsEmf}

| Όνομα | Περιγραφή |
| --- | --- |
| writeAsEmf (OutputStream) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή-στόχος |

 ****Επιστρέφει:****
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentNullException | Η ροή-στόχος είναι {@code null} |
 


---


### writeAsSvg {#writeAsSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| writeAsSvg (OutputStream) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή-στόχος |

 ****Επιστρέφει:****
void


---


### writeAsSvg {#writeAsSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| writeAsSvg (OutputStream, [SVGOptions](../svgoptions)) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή-στόχος |
| svgOptions | [SVGOptions](../svgoptions) | Επιλογές δημιουργίας SVG |

 ****Επιστρέφει:****
void


---