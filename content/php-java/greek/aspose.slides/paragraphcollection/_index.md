---
title: ParagraphCollection
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs

url: /el/aspose.slides/paragraphcollection/
---
## ParagraphCollection κλάση

Αντιπροσωπεύει μια συλλογή παραγράφων.

### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add ([Paragraph](../paragraph)) | Προσθέτει ένα Paragraph στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Paragraph](../paragraph) | Το Paragraph που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
void


---


### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add ([ParagraphCollection](../paragraphcollection)) | Προσθέτει περιεχόμενο του ParagraphCollection στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ParagraphCollection](../paragraphcollection) | Το ParagraphCollection που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int


---


### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (String) | Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά html στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Κείμενο HTML. |

**Επιστρέφει:**
void


---


### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά html στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Κείμενο HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Αντικείμενο callback resolver που επιλύει URIs και ανακτά τα αναφερόμενα αντικείμενα. |
| uri | String | URI για την προσθήκη εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. Η καθορισμένη resolver μπορεί ενδεχομένως να εισαγάγει ευπάθεια. Χρησιμοποιήστε με προσοχή. |

**Επιστρέφει:**
void


---


### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά html στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Κείμενο HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Αντικείμενο callback resolver που επιλύει URIs και ανακτά τα αναφερόμενα αντικείμενα. |
| uri | String | URI για την προσθήκη εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. Η καθορισμένη resolver μπορεί ενδεχομένως να εισαγάγει ευπάθεια. Χρησιμοποιήστε με προσοχή. |

**Επιστρέφει:**
void


---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |

**Επιστρέφει:**
void


---


### contains {#contains}

| Όνομα | Περιγραφή |
| --- | --- |
| contains ([Paragraph](../paragraph)) | Καθορίζει εάν το IGenericCollection περιέχει συγκεκριμένη τιμή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | Το αντικείμενο που θα εντοπιστεί στο IGenericCollection. |

**Επιστρέφει:**
boolean


---


### copyTo {#copyTo}

| Όνομα | Περιγραφή |
| --- | --- |
| copyTo (com.aspose.slides.IParagraph[], int) | Αντιγράφει τα στοιχεία του IGenericCollection σε έναν Array, αρχίζοντας από συγκεκριμένο δείκτη Array. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.slides.IParagraph[] | Ο μονοδιάστατος Array που είναι ο προορισμός των αντιγραφόμενων στοιχείων από το IGenericCollection. Ο Array πρέπει να έχει μηδενική βάση δείκτη. |
| arrayIndex | int | Ο δείκτης μηδενικής βάσης στον array όπου ξεκινά η αντιγραφή. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Ο αριθμός των στοιχείων στην πηγή IGenericCollection είναι μεγαλύτερος από το διαθέσιμο χώρο από το arrayIndex μέχρι το τέλος του προορισμού array. |


---


### exportToHtml {#exportToHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| exportToHtml (int, int, [TextToHtmlConversionOptions](../texttohtmlconversionoptions)) | Μετατρέπει τις καθορισμένες παραγράφους σε HTML και το επιστρέφει ως αντικείμενο String. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstParagraphIndex | int | Δείκτης πρώτης παραγράφου int |
| paragraphsCount | int | Αριθμός παραγράφων int |
| options | [TextToHtmlConversionOptions](../texttohtmlconversionoptions) | Επιλογές μετατροπής ITextToHtmlConversionOptions |

**Επιστρέφει:**
String


---


### getCount {#getCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getCount () | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο ανάγνωση int. |

**Επιστρέφει:**
int


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση μιας συλλογής παραγράφων. Μόνο ανάγνωση IPresentation. |

**Επιστρέφει:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει τη γονική διαφάνεια μιας συλλογής παραγράφων. Μόνο ανάγνωση BaseSlide. |

**Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Λαμβάνει το στοιχείο στην καθορισμένη θέση. |

**Επιστρέφει:**
[Paragraph](../paragraph)


---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([Paragraph](../paragraph)) | Καθορίζει τον δείκτη ενός συγκεκριμένου στοιχείου στη Λίστα. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | Το αντικείμενο που θα εντοπιστεί στη Λίστα. |

**Επιστρέφει:**
int


---


### insert {#insert}

| Όνομα | Περιγραφή |
| --- | --- |
| insert (int, [Paragraph](../paragraph)) | Εισάγει ένα Paragraph στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης όπου θα εισαχθεί το Paragraph. |
| value | [Paragraph](../paragraph) | Το Paragraph που θα εισαχθεί. |

**Επιστρέφει:**
void


---


### insert {#insert}

| Όνομα | Περιγραφή |
| --- | --- |
| insert (int, [ParagraphCollection](../paragraphcollection)) | Εισάγει περιεχόμενο του ParagraphCollection στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης όπου θα εισαχθούν οι παραγράφοι. |
| value | [ParagraphCollection](../paragraphcollection) | Οι παράγραφοι που θα εισαχθούν. |

**Επιστρέφει:**
void


---


### isReadOnly {#isReadOnly}

| Όνομα | Περιγραφή |
| --- | --- |
| isReadOnly () | Λαμβάνει τιμή που υποδεικνύει εάν το IGenericCollection είναι μόνο ανάγνωση. Μόνο ανάγνωση boolean. |

**Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν enumerator που διασχίζει τη συλλογή. |

**Επιστρέφει:**



---


### iteratorJava {#iteratorJava}

| Όνομα | Περιγραφή |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

**Επιστρέφει:**



---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([Paragraph](../paragraph)) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το IGenericCollection. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | Το αντικείμενο που θα αφαιρεθεί από το IGenericCollection. |

**Επιστρέφει:**
boolean

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| NotSupportedException | Το IGenericCollection είναι μόνο ανάγνωση. |


---


### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Αφαιρεί το στοιχείο στην καθορισμένη θέση της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

**Επιστρέφει:**
void


---  