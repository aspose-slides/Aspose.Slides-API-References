---
title: Presentation
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/presentation/
---
## Presentation κλάση

  Αντιπροσωπεύει μια παρουσία Microsoft PowerPoint.

### Presentation {#Presentation}

| Όνομα | Περιγραφή |
| --- | --- |
| Presentation() | Αυτή η λειτουργία δημιουργεί νέα παρουσία από την αρχή. Η δημιουργημένη παρουσία έχει μία κενή διαφάνεια. |

**Τιμή επιστροφής:**
Presentation


---


### Presentation {#Presentation}

| Όνομα | Περιγραφή |
| --- | --- |
| Presentation([LoadOptions](../loadoptions)) | Αυτή η λειτουργία δημιουργεί νέα παρουσία από την αρχή. Η δημιουργημένη παρουσία έχει μία κενή διαφάνεια. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| loadOptions | [LoadOptions](../loadoptions) | Πρόσθετες επιλογές φόρτωσης. |

**Τιμή επιστροφής:**
Presentation


---


### Presentation {#Presentation}

| Όνομα | Περιγραφή |
| --- | --- |
| Presentation(InputStream) | Αυτή η λειτουργία είναι ο κύριος μηχανισμός ανάγνωσης υπάρχουσας Παρουσίασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | InputStream | Ροή εισόδου. |

**Τιμή επιστροφής:**
Presentation


---


### Presentation {#Presentation}

| Όνομα | Περιγραφή |
| --- | --- |
| Presentation(InputStream, [LoadOptions](../loadoptions)) | Αυτή η λειτουργία είναι ο κύριος μηχανισμός ανάγνωσης υπάρχουσας Παρουσίασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | InputStream | Ροή εισόδου. |
| loadOptions | [LoadOptions](../loadoptions) | Πρόσθετες επιλογές φόρτωσης. |

**Τιμή επιστροφής:**
Presentation


---


### Presentation {#Presentation}

| Όνομα | Περιγραφή |
| --- | --- |
| Presentation(String) | Αυτή η λειτουργία λαμβάνει ένα μονοπάτι αρχείου πηγής από το οποίο διαβάζονται τα περιεχόμενα της Παρουσίασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | String | Αρχείο εισόδου. |

**Τιμή επιστροφής:**
Presentation

**Σφάλμα**

| Σφάλμα | Κατάσταση |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Επιδίωξη όταν το αρχείο εισόδου έχει μηδενικό μήκος |


---


### Presentation {#Presentation}

| Όνομα | Περιγραφή |
| --- | --- |
| Presentation(String, [LoadOptions](../loadoptions)) | Αυτή η λειτουργία λαμβάνει ένα μονοπάτι αρχείου πηγής από το οποίο διαβάζονται τα περιεχόμενα της Παρουσίασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | String | Αρχείο εισόδου. |
| loadOptions | [LoadOptions](../loadoptions) | Πρόσθετες επιλογές φόρτωσης. |

**Τιμή επιστροφής:**
Presentation

**Σφάλμα**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Επιδίωξη όταν το αρχείο εισόδου έχει μηδενικό μήκος |


---


### dispose {#dispose}

| Όνομα | Περιγραφή |
| --- | --- |
| dispose () | Αποδεσμεύει όλους τους πόρους που χρησιμοποιεί αυτό το αντικείμενο Presentation. |

**Τιμή επιστροφής:**
void


---


### getAllCustomXmlParts {#getAllCustomXmlParts}

| Όνομα | Περιγραφή |
| --- | --- |
| getAllCustomXmlParts () | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσία. Μόνο προς ανάγνωση ICustomXmlPart[]. |

**Τιμή επιστροφής:**
[CustomXmlPart](../customxmlpart)


---


### getAudios {#getAudios}

| Όνομα | Περιγραφή |
| --- | --- |
| getAudios () | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσία. Μόνο προς ανάγνωση IAudioCollection. |

**Τιμή επιστροφής:**
[AudioCollection](../audiocollection)


---


### getCommentAuthors {#getCommentAuthors}

| Όνομα | Περιγραφή |
| --- | --- |
| getCommentAuthors () | Επιστρέφει τη συλλογή συγγραφέων σχολίων. Μόνο προς ανάγνωση ICommentAuthorCollection. |

**Τιμή επιστροφής:**
[CommentAuthorCollection](../commentauthorcollection)


---


### getCurrentDateTime {#getCurrentDateTime}

| Όνομα | Περιγραφή |
| --- | --- |
| getCurrentDateTime () | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσουν το περιεχόμενο των πεδίων datetime. Προεπιλογή είναι η ώρα δημιουργίας αυτού του αντικειμένου Presentation. Ανάγνωση/εγγραφή java.util.Date. |

**Τιμή επιστροφής:**
Date


---


### getCustomData {#getCustomData}

| Όνομα | Περιγραφή |
| --- | --- |
| getCustomData () | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. Μόνο προς ανάγνωση ICustomData. |

**Τιμή επιστροφής:**
[CustomData](../customdata)


---


### getDefaultTextStyle {#getDefaultTextStyle}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefaultTextStyle () | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. Μόνο προς ανάγνωση ITextStyle. |

**Τιμή επιστροφής:**
[TextStyle](../textstyle)


---


### getDigitalSignatures {#getDigitalSignatures}

| Όνομα | Περιγραφή |
| --- | --- |
| getDigitalSignatures () | Επιστρέφει τη συλλογή ψηφιακών υπογραφών που χρησιμοποιούνται για την υπογραφή της παρουσίασης. Μόνο προς ανάγνωση IDigitalSignatureCollection. |

**Τιμή επιστροφής:**
[DigitalSignatureCollection](../digitalsignaturecollection)


---


### getDocumentProperties {#getDocumentProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getDocumentProperties () | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. Μόνο προς ανάγνωση IDocumentProperties. |

**Τιμή επιστροφής:**
[DocumentProperties](../documentproperties)


---


### getFirstSlideNumber {#getFirstSlideNumber}

| Όνομα | Περιγραφή |
| --- | --- |
| getFirstSlideNumber () | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. |

**Τιμή επιστροφής:**
int


---


### getFontsManager {#getFontsManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getFontsManager () | Επιστρέφει τον διαχειριστή γραμματοσειρών. Μόνο προς ανάγνωση IFontsManager. |

**Τιμή επιστροφής:**
[FontsManager](../fontsmanager)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeaderFooterManager () | Επιστρέφει τον τρέχοντα διαχειριστή κεφαλίδων/υποσέλιδων. Μόνο προς ανάγνωση IPresentationHeaderFooterManager. |

**Τιμή επιστροφής:**
[PresentationHeaderFooterManager](../presentationheaderfootermanager)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkQueries () | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (εκτός από master, layout, notes). Μόνο προς ανάγνωση IHyperlinkQueries. |

**Τιμή επιστροφής:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getImages {#getImages}

| Όνομα | Περιγραφή |
| --- | --- |
| getImages () | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Μόνο προς ανάγνωση IImageCollection. |

**Τιμή επιστροφής:**
[ImageCollection](../imagecollection)


---


### getImages {#getImages}

| Όνομα | Περιγραφή |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions)) | Επιστρέφει αντικείμενα Image για όλες τις διαφάνειες μιας παρουσίασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές Tiff. |

**Τιμή επιστροφής:**
IImage


---


### getImages {#getImages}

| Όνομα | Περιγραφή |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[]) | Επιστρέφει αντικείμενα Thumbnail Image για συγκεκριμένες διαφάνειες μιας παρουσίασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές Tiff. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |

**Τιμή επιστροφής:**
IImage


---


### getImages {#getImages}

| Όνομα | Περιγραφή |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), float, float) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές Tiff. |
| scaleX | float | Η τιμή κλίμακας κατά την κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή κλίμακας κατά την κατεύθυνση του άξονα y. |

**Τιμή επιστροφής:**
IImage


---


### getImages {#getImages}

| Όνομα | Περιγραφή |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[], float, float) | Επιστρέφει αντικείμενα Thumbnail Image για συγκεκριμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές Tiff. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| scaleX | float | Η τιμή κλίμακας κατά την κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή κλίμακας κατά την κατεύθυνση του άξονα y. |

**Τιμή επιστροφής:**
IImage


---


### getImages {#getImages}

| Όνομα | Περιγραφή |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), Dimension) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με συγκεκριμένο μέγεθος. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές Tiff. |
| imageSize | Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Τιμή επιστροφής:**
IImage


---


### getImages {#getImages}

| Όνομα | Περιγραφή |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[], Dimension) | Επιστρέφει αντικείμενα Thumbnail Image για συγκεκριμένες διαφάνειες μιας παρουσίασης με συγκεκριμένο μέγεθος. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Επιλογές Tiff. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| imageSize | Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Τιμή επιστροφής:**
IImage


---


### getLayoutSlides {#getLayoutSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getLayoutSlides () | Επιστρέφει λίστα όλων των διαφανειών διάταξης που ορίζονται στην παρουσίαση. Μόνο προς ανάγνωση IGlobalLayoutSlideCollection. Μπορείτε να έχετε πρόσβαση σε εναλλακτικό API για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα IMasterSlide.LayoutSlides. |

**Τιμή επιστροφής:**
[GlobalLayoutSlideCollection](../globallayoutslidecollection)


---


### getMasterHandoutSlideManager {#getMasterHandoutSlideManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getMasterHandoutSlideManager () | Επιστρέφει το διαχειριστή master χρονολόγιου. Μόνο προς ανάγνωση IMasterHandoutSlideManager. |

**Τιμή επιστροφής:**
MasterHandoutSlideManager


---


### getMasterNotesSlideManager {#getMasterNotesSlideManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getMasterNotesSlideManager () | Επιστρέφει το διαχειριστή master σημειώσεων. Μόνο προς ανάγνωση IMasterNotesSlideManager. |

**Τιμή επιστροφής:**
MasterNotesSlideManager


---


### getMasterTheme {#getMasterTheme}

| Όνομα | Περιγραφή |
| --- | --- |
| getMasterTheme () | Επιστρέφει το master θέμα. Μόνο προς ανάγνωση IMasterTheme. |

**Τιμή επιστροφής:**
[MasterTheme](../mastertheme)


---


### getMasters {#getMasters}

| Όνομα | Περιγραφή |
| --- | --- |
| getMasters () | Επιστρέφει λίστα όλων των master διαφανειών που ορίζονται στην παρουσίαση. Μόνο προς ανάγνωση IMasterSlideCollection. |

**Τιμή επιστροφής:**
[MasterSlideCollection](../masterslidecollection)


---


### getNotesSize {#getNotesSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getNotesSize () | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων. Μόνο προς ανάγνωση INotesSize. |

**Τιμή επιστροφής:**
[NotesSize](../notessize)


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την πατρική παρουσίαση ενός κειμένου. Μόνο προς ανάγνωση IPresentation. |

**Τιμή επιστροφής:**
[Presentation](../presentation)


---


### getProtectionManager {#getProtectionManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getProtectionManager () | Λαμβάνει τον διαχειριστή δικαιωμάτων για αυτήν την παρουσίαση. Μόνο προς ανάγνωση IProtectionManager. |

**Τιμή επιστροφής:**
[ProtectionManager](../protectionmanager)


---


### getSections {#getSections}

| Όνομα | Περιγραφή |
| --- | --- |
| getSections () | Επιστρέφει λίστα όλων των ενοτήτων διαφανειών που ορίζονται στην παρουσίαση. Μόνο προς ανάγνωση ISectionCollection. |

**Τιμή επιστροφής:**
[SectionCollection](../sectioncollection)


---


### getSensitivityLabels {#getSensitivityLabels}

| Όνομα | Περιγραφή |
| --- | --- |
| getSensitivityLabels () | Επιστρέφει τη συλλογή ετικετών ευαισθησίας που έχουν εφαρμοστεί στο έγγραφο παρουσίασης. Μόνο προς ανάγνωση ISensitivityLabelCollection. |

**Τιμή επιστροφής:**
[SensitivityLabelCollection](../sensitivitylabelcollection)


---


### getSlideById {#getSlideById}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlideById (long) | Επιστρέφει μια Slide, MasterSlide ή LayoutSlide κατά Id. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | long | Id μιας διαφάνειας. |

**Τιμή επιστροφής:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSlideShowSettings {#getSlideShowSettings}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlideShowSettings () | Επιστρέφει τις ρυθμίσεις προβολής διαφανειών για την παρουσίαση. |

**Τιμή επιστροφής:**
SlideShowSettings


---


### getSlideSize {#getSlideSize}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlideSize () | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο προς ανάγνωση ISlideSize. |

**Τιμή επιστροφής:**
[SlideSize](../slidesize)


---


### getSlides {#getSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlides () | Επιστρέφει λίστα όλων των διαφανειών που ορίζονται στην παρουσίαση. Μόνο προς ανάγνωση ISlideCollection. |

**Τιμή επιστροφής:**
[SlideCollection](../slidecollection)


---


### getSourceFormat {#getSourceFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getSourceFormat () | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. Μόνο προς ανάγνωση SourceFormat. |

**Τιμή επιστροφής:**
int


---


### getVbaProject {#getVbaProject}

| Όνομα | Περιγραφή |
| --- | --- |
| getVbaProject () | Λαμβάνει ή ορίζει το έργο VBA με μακροεντολές παρουσίασης. Ανάγνωση/εγγραφή IVbaProject. |

**Τιμή επιστροφής:**
[VbaProject](../vbaproject)


---


### getVideos {#getVideos}

| Όνομα | Περιγραφή |
| --- | --- |
| getVideos () | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο για ανάγνωση IVideoCollection. |

**Επιστρέφει:**  
[VideoCollection](../videocollection)

---

### getViewProperties {#getViewProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getViewProperties () | Λαμβάνει τις ιδιότητες προβολής ολόκληρης παρουσίασης. Μόνο για ανάγνωση IViewProperties. |

**Επιστρέφει:**  
[ViewProperties](../viewproperties)

---

### highlightRegex {#highlightRegex}

| Όνομα | Περιγραφή |
| --- | --- |
| highlightRegex (Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | Pattern | Η κανονική έκφραση java.util.regex.Pattern για την λήψη συμβολοσειρών προς επισήμανση. |
| highlightColor | Color | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [IFindResultCallback](../ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης IFindResultCallback. |

**Επιστρέφει:**  
void

---

### highlightText {#highlightText}

| Όνομα | Περιγραφή |
| --- | --- |
| highlightText (String, Color) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Το κείμενο προς επισήμανση. |
| highlightColor | Color | Το χρώμα για την επισήμανση του κειμένου. |

**Επιστρέφει:**  
void

---

### highlightText {#highlightText}

| Όνομα | Περιγραφή |
| --- | --- |
| highlightText (String, Color, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Το κείμενο προς επισήμανση. |
| highlightColor | Color | Το χρώμα για την επισήμανση του κειμένου. |
| options | [TextSearchOptions](../textsearchoptions) | Επιλογές αναζήτησης κειμένου ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης IFindResultCallback. |

**Επιστρέφει:**  
void

---

### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Όνομα | Περιγραφή |
| --- | --- |
| joinPortionsWithSameFormatting () | Ενώνει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |

**Επιστρέφει:**  
void

---

### replaceRegex {#replaceRegex}

| Όνομα | Περιγραφή |
| --- | --- |
| replaceRegex (Pattern, String, [IFindResultCallback](../ifindresultcallback)) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με τη συγκεκριμένη συμβολοσειρά. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | Pattern | Η κανονική έκφραση java.util.regex.Pattern για τη λήψη συμβολοσειρών προς αντικατάσταση. |
| newText | String | Η συμβολοσειρά που αντικαθιστά όλες τις εμφανίσεις των συμβολοσειρών που πρέπει να αντικατασταθούν. |
| callback | [IFindResultCallback](../ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης IFindResultCallback. |

**Επιστρέφει:**  
void

---

### replaceText {#replaceText}

| Όνομα | Περιγραφή |
| --- | --- |
| replaceText (String, String, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| oldText | String | Η συμβολοσειρά που θα αντικατασταθεί. |
| newText | String | Η συμβολοσειρά που αντικαθιστά όλες τις εμφανίσεις του oldText. |
| options | [TextSearchOptions](../textsearchoptions) | Επιλογές αναζήτησης κειμένου ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης IFindResultCallback. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [RenderingOptions](../renderingoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [RenderingOptions](../renderingoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [PptOptions](../pptoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptOptions](../pptoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [XamlOptions](../xamloptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XamlOptions](../xamloptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [SVGOptions](../svgoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SVGOptions](../svgoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [MarkdownSaveOptions](../markdownsaveoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [HtmlOptions](../htmloptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [HtmlOptions](../htmloptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [PdfOptions](../pdfoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PdfOptions](../pdfoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέ φει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [SwfOptions](../swfoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SwfOptions](../swfoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [TiffOptions](../tiffoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [TiffOptions](../tiffoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [Html5Options](../html5options)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [Html5Options](../html5options) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [XpsOptions](../xpsoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XpsOptions](../xpsoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [SaveOptions](../saveoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SaveOptions](../saveoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέ φει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [GifOptions](../gifoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [GifOptions](../gifoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int, [PptxOptions](../pptxoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptxOptions](../pptxoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέφει:**  
void

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int, [RenderingOptions](../renderingoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [RenderingOptions](../renderingoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέ φει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή εκτός Office 2007-2010 |

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int, [PptOptions](../pptoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptOptions](../pptoptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέ φει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή εκτός Office 2007-2010 |

---

### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int, [XamlOptions](../xamloptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή και με επιπλέον επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XamlOptions](../xamloptions) | Επιπλέον επιλογές μορφής. |

**Επιστρέ φει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή εκτός Office 2007-2010 |

---
| save (OutputStream, int, [SVGOptions](../svgoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SVGOptions](../svgoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [MarkdownSaveOptions](../markdownsaveoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [HtmlOptions](../htmloptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [HtmlOptions](../htmloptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [PdfOptions](../pdfoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PdfOptions](../pdfoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [SwfOptions](../swfoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SwfOptions](../swfoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [TiffOptions](../tiffoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [TiffOptions](../tiffoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [Html5Options](../html5options)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [Html5Options](../html5options) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [XpsOptions](../xpsoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XpsOptions](../xpsoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [SaveOptions](../saveoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SaveOptions](../saveoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [GifOptions](../gifoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [GifOptions](../gifoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [PptxOptions](../pptxoptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ρεύμα με τη μορφή που καθορίζεται και με πρόσθετες επιλογές. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptxOptions](../pptxoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| NotSupportedException | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε μορφή που δεν είναι Office 2007-2010 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save ([XamlOptions](../xamloptions)) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [XamlOptions](../xamloptions) | Οι επιλογές μορφής XAML. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [RenderingOptions](../renderingoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [RenderingOptions](../renderingoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [PptOptions](../pptoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptOptions](../pptoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [XamlOptions](../xamloptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XamlOptions](../xamloptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [SVGOptions](../svgoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SVGOptions](../svgoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [HtmlOptions](../htmloptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [HtmlOptions](../htmloptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [PdfOptions](../pdfoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PdfOptions](../pdfoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [SwfOptions](../swfoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SwfOptions](../swfoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [TiffOptions](../tiffoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή διατηρώντας τον αριθμό των σελίδων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή στο δημιουργούμενο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [TiffOptions](../tiffoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void
| save (String, int[], int, [Html5Options](../html5options)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [Html5Options](../html5options) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int[], int, [XpsOptions](../xpsoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XpsOptions](../xpsoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int[], int, [SaveOptions](../saveoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SaveOptions](../saveoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int[], int, [GifOptions](../gifoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [GifOptions](../gifoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (String, int[], int, [PptxOptions](../pptxoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptxOptions](../pptxoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

**Τιμή Επιστροφής:**
void


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [RenderingOptions](../renderingoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [RenderingOptions](../renderingoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [PptOptions](../pptoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptOptions](../pptoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [XamlOptions](../xamloptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XamlOptions](../xamloptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [SVGOptions](../svgoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SVGOptions](../svgoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [HtmlOptions](../htmloptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [HtmlOptions](../htmloptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [PdfOptions](../pdfoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PdfOptions](../pdfoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [SwfOptions](../swfoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SwfOptions](../swfoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [TiffOptions](../tiffoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [TiffOptions](../tiffoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [Html5Options](../html5options)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [Html5Options](../html5options) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [XpsOptions](../xpsoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [XpsOptions](../xpsoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [SaveOptions](../saveoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [SaveOptions](../saveoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [GifOptions](../gifoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [GifOptions](../gifoptions) | Επιπλέον επιλογές μορφής. |

**Τιμή Επιστροφής:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται ένα μη υποστηριζόμενο SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Όνομα | Περιγραφή |
| --- | --- |
| save (OutputStream, int[], int, [PptxOptions](../pptxoptions)) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή, διατηρώντας τον αριθμό σελίδας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [PptxOptions](../pptxoptions) | Πρόσθετες επιλογές μορφής. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| InvalidOperationException | Όταν χρησιμοποιείται μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

---

### setCurrentDateTime {#setCurrentDateTime}

| Όνομα | Περιγραφή |
| --- | --- |
| setCurrentDateTime (Date) | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του αντικειμένου Presentation από προεπιλογή. Ανάγνωση/εγγραφή java.util.Date. |

**Επιστρέφει:**
void

---

### setFirstSlideNumber {#setFirstSlideNumber}

| Όνομα | Περιγραφή |
| --- | --- |
| setFirstSlideNumber (int) | Αντιπροσωπεύει τον αριθμό της πρώτης διαφάνειας στην παρουσίαση |

**Επιστρέφει:**
void

---

### setVbaProject {#setVbaProject}

| Όνομα | Περιγραφή |
| --- | --- |
| setVbaProject ([VbaProject](../vbaproject)) | Λαμβάνει ή ορίζει το έργο VBA με μακροεντολές παρουσίασης. Ανάγνωση/εγγραφή IVbaProject. |

**Επιστρέφει:**
void

---