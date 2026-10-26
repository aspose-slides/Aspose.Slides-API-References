---
title: MasterSlide
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/masterslide/
---
## MasterSlide κλάση

Αναπαριστά μια κύρια διαφάνεια σε μια παρουσίαση.

### applyExternalThemeToDependingSlides {#applyExternalThemeToDependingSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| applyExternalThemeToDependingSlides (String) | Δημιουργεί μια νέα κύρια διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζοντας ένα εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτημένες διαφάνειες. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Διαδρομή προς το αρχείο εξωτερικού θέματος (.thmx). |

**Επιστρέφει:**
[MasterSlide](../masterslide)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxReadException | Όταν το εξωτερικό θέμα δεν μπορεί να εφαρμοστεί. |

---


### getBodyStyle {#getBodyStyle}

| Όνομα | Περιγραφή |
| --- | --- |
| getBodyStyle () | Επιστρέφει το στυλ κειμένου σώματος. Μόνο για ανάγνωση ITextStyle. |

**Επιστρέφει:**
[TextStyle](../textstyle)

---


### getDependingSlides {#getDependingSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getDependingSlides () | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν την κύρια διαφάνεια. |

**Επιστρέφει:**
[Slide](../slide)

---


### getDrawingGuides {#getDrawingGuides}

| Όνομα | Περιγραφή |
| --- | --- |
| getDrawingGuides () | Επιστρέφει μια συλλογή οδηγών σχεδίασης για την κύρια διαφάνεια. Μόνο για ανάγνωση IDrawingGuidesCollection |

**Επιστρέφει:**
[DrawingGuidesCollection](../drawingguidescollection)

---


### getHeaderFooterManager {#getHeaderFooterManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeaderFooterManager () | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας. Μόνο για ανάγνωση IMasterSlideHeaderFooterManager. |

**Επιστρέφει:**
[MasterSlideHeaderFooterManager](../masterslideheaderfootermanager)

---


### getLayoutSlides {#getLayoutSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getLayoutSlides () | Επιστρέφει τη συλλογή των παιδιών διαφανειών διάταξης για αυτήν την κύρια διαφάνεια. Μόνο για ανάγνωση IMasterLayoutSlideCollection. Μπορείτε να αποκτήσετε πρόσβαση σε εναλλακτικό API για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα ( IPresentation#getLayoutSlides). |

**Επιστρέφει:**
[MasterLayoutSlideCollection](../masterlayoutslidecollection)

---


### getName {#getName}

| Όνομα | Περιγραφή |
| --- | --- |
| getName () | Επιστρέφει ή ορίζει το όνομα μιας κύριας διαφάνειας. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String

---


### getOtherStyle {#getOtherStyle}

| Όνομα | Περιγραφή |
| --- | --- |
| getOtherStyle () | Επιστρέφει το στυλ ενός άλλου κειμένου. Μόνο για ανάγνωση ITextStyle. |

**Επιστρέφει:**
[TextStyle](../textstyle)

---


### getPreserve {#getPreserve}

| Όνομα | Περιγραφή |
| --- | --- |
| getPreserve () | Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια θα διαγραφεί όταν όλες οι διαφάνειες που την ακολουθούν διαγραφούν. Σημείωση: το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα κάποια αχρησιμοποίητη κύρια διαφάνεια· για να αφαιρέσετε πραγματικά αχρησιμοποίητες κύριες διαφάνειες, καλέστε MasterSlideCollection#removeUnused(boolean). Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean

---


### getShowMasterShapes {#getShowMasterShapes}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowMasterShapes () | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για την ίδια την κύρια διαφάνεια αυτή η ιδιότητα πάντα επιστρέφει false. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| NotSupportedException | Λαμβάνεται εάν οριστεί {@code true} για την κύρια διαφάνεια. |

---


### getThemeManager {#getThemeManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getThemeManager () | Επιστρέφει το διαχειριστή θέματος. Μόνο για ανάγνωση IMasterThemeManager. |

**Επιστρέφει:**
[MasterThemeManager](../masterthememanager)

---


### getTitleStyle {#getTitleStyle}

| Όνομα | Περιγραφή |
| --- | --- |
| getTitleStyle () | Επιστρέφει το στυλ κειμένου τίτλου. Μόνο για ανάγνωση ITextStyle. |

**Επιστρέφει:**
[TextStyle](../textstyle)

---


### hasDependingSlides {#hasDependingSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| hasDependingSlides () | Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτήν την κύρια διαφάνεια. Μόνο για ανάγνωση boolean. |

**Επιστρέφει:**
boolean

---


### setName {#setName}

| Όνομα | Περιγραφή |
| --- | --- |
| setName (String) | Επιστρέφει ή ορίζει το όνομα μιας κύριας διαφάνειας. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void

---


### setPreserve {#setPreserve}

| Όνομα | Περιγραφή |
| --- | --- |
| setPreserve (boolean) | Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια θα διαγραφεί όταν όλες οι διαφάνειες που την ακολουθούν διαγραφούν. Σημείωση: το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα κάποια αχρησιμοποίητη κύρια διαφάνεια· για να αφαιρέσετε πραγματικά αχρησιμοποίητες κύριες διαφάνειες, καλέστε MasterSlideCollection#removeUnused(boolean). Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void

---


### setShowMasterShapes {#setShowMasterShapes}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowMasterShapes (boolean) | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για την ίδια την κύρια διαφάνεια αυτή η ιδιότητα πάντα επιστρέφει false. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| NotSupportedException | Λαμβάνεται εάν οριστεί {@code true} για την κύρια διαφάνεια. |

---