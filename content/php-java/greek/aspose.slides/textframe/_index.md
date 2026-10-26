---
title: TextFrame
second_title: Aspose.Sildes για PHP μέσω Αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/textframe/
---
## TextFrame κλάση

  Αναπαριστά ένα TextFrame.
 
### getHyperlinkQueries {#getHyperlinkQueries}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkQueries () | Provides easy access to contained hyperlinks. Μόνο ανάγνωση IHyperlinkQueries. |

 **Επιστρέφει:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getParagraphs {#getParagraphs}

| Όνομα | Περιγραφή |
| --- | --- |
| getParagraphs () | Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο. Μόνο ανάγνωση IParagraphCollection. |

 **Επιστρέφει:**
[ParagraphCollection](../paragraphcollection)


---


### getParentCell {#getParentCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentCell () | Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή ICell. Μόνο ανάγνωση ICell. |

 **Επιστρέφει:**
[Cell](../cell)


---


### getParentShape {#getParentShape}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentShape () | Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή IShape. Μόνο ανάγνωση IShape. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση ενός TextFrame. Μόνο ανάγνωση IPresentation. |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει τη γονική διαφάνεια ενός TextFrame. Μόνο ανάγνωση IBaseSlide. |

 **Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| Όνομα | Περιγραφή |
| --- | --- |
| getText () | Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. Ανάγνωση/Εγγραφή String. Τιμή: Το κείμενο. |

 **Επιστρέφει:**
String


---


### getTextFrameFormat {#getTextFrameFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getTextFrameFormat () | Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το TextFrame. Μόνο ανάγνωση ITextFrameFormat. |

 **Επιστρέφει:**
[TextFrameFormat](../textframeformat)


---


### highlightRegex {#highlightRegex}

| Όνομα | Περιγραφή |
| --- | --- |
| highlightRegex (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | String | Κείμενο της κανονικής έκφρασης για λήψη κειμένου προς επισήμανση. |
| highlightColor | Color | Το χρώμα για την επισήμανση του κειμένου. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Επιλογές επισήμανσης. |

 **Επιστρέφει:**
void


---


### highlightRegex {#highlightRegex}

| Όνομα | Περιγραφή |
| --- | --- |
| highlightRegex (Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη συμβολοσειρών προς επισήμανση. |
| highlightColor | Color | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [IFindResultCallback](../ifindresultcallback) | Το αντικείμενο κλήσης επιστροφής για λήψη αποτελεσμάτων αναζήτησης IFindResultCallback. |

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
| text | String | Το δείγμα κειμένου προς επισήμανση. |
| highlightColor | Color | Το χρώμα για την επισήμανση του κειμένου. |

 **Επιστρέφει:**
void


---


### highlightText {#highlightText}

| Όνομα | Περιγραφή |
| --- | --- |
| highlightText (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Το κείμενο προς επισήμανση. |
| highlightColor | Color | Το χρώμα για την επισήμανση του κειμένου. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Επιλογές επισήμανσης. |

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
| callback | [IFindResultCallback](../ifindresultcallback) | Το αντικείμενο κλήσης επιστροφής για λήψη αποτελεσμάτων αναζήτησης IFindResultCallback. |

 **Επιστρέφει:**
void


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Όνομα | Περιγραφή |
| --- | --- |
| joinPortionsWithSameFormatting () | Ενώνει τμήματα με ίδια μορφοποίηση σε όλες τις παραγράφους. |

 **Επιστρέφει:**
void


---


### replaceRegex {#replaceRegex}

| Όνομα | Περιγραφή |
| --- | --- |
| replaceRegex (Pattern, String, [IFindResultCallback](../ifindresultcallback)) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη συμβολοσειρών προς αντικατάσταση. |
| newText | String | Η συμβολοσειρά για αντικατάσταση όλων των εμφανίσεων των συμβολοσειρών που πρέπει να αντικατασταθούν. |
| callback | [IFindResultCallback](../ifindresultcallback) | Αντικείμενο κλήσης επιστροφής για αποθήκευση του αποτελέσματος της λειτουργίας αντικατάστασης IFindResultCallback. |

 **Επιστεύει:**
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
| newText | String | Η συμβολοσειρά για αντικατάσταση όλων των εμφανίσεων του oldText. |
| options | [TextSearchOptions](../textsearchoptions) | Επιλογές αναζήτησης κειμένου ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | Αντικείμενο κλήσης επιστροφής για αποθήκευση του αποτελέσματος της λειτουργίας αντικατάστασης IFindResultCallback. |

 **Επιστρέφει:**
void


---


### setText {#setText}

| Όνομα | Περιγραφή |
| --- | --- |
| setText (String) | Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. Ανάγνωση/Εγγραφή String. Τιμή: Το κείμενο. |

 **Επιστρέφει:**
void


---


### splitTextByColumns {#splitTextByColumns}

| Όνομα | Περιγραφή |
| --- | --- |
| splitTextByColumns () | Διαιρεί το περιεχόμενο κειμένου του ITextFrame σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο. |

 **Επιστρέφει:**
String


---