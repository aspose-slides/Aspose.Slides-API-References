---
title: Paragraph
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs

url: /el/aspose.slides/paragraph/
---
## Paragraph κλάση

Αντιπροσωπεύει μια παράγραφο κειμένου.

### Paragraph {#Paragraph}

| Όνομα | Περιγραφή |
| --- | --- |
| Paragraph() | Αρχικοποιεί μια νέα παρουσία της κλάσης Paragraph με προεπιλεγμένες ιδιότητες. |

**Επιστρέφει:**
Paragraph

---

### Paragraph {#Paragraph}

| Όνομα | Περιγραφή |
| --- | --- |
| Paragraph([Paragraph](../paragraph)) | Συνάρτηση αντιγραφής που αρχικοποιεί μια νέα παρουσία της κλάσης Paragraph. |

**Επιστρέφει:**
Paragraph

---

### getEndParagraphPortionFormat {#getEndParagraphPortionFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getEndParagraphPortionFormat () | Καθορίζει τις ιδιότητες του τμήματος που θα χρησιμοποιηθούν εάν ένα άλλο τμήμα εισαχθεί μετά το τελευταίο. |

**Επιστρέφει:**
[PortionFormat](../portionformat)

---

### getLinesCount {#getLinesCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getLinesCount () | Λαμβάνει τον αριθμό γραμμών σε μια παράγραφο. |

**Επιστρέφει:**
int

---

### getParagraphFormat {#getParagraphFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getParagraphFormat () | Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. Μόνο για ανάγνωση IParagraphFormat. Το αντικείμενο μορφοποίησης περιέχει τις παραμέτρους μορφοποίησης που ορίζονται μόνο για την τρέχουσα παράγραφο, οι κληματισμένες δεδομένες δεν εφαρμόζονται. Για την απόκτηση των αποτελεσματικών τιμών, συμπεριλαμβανομένων των κλημένων, χρησιμοποιήστε τη μέθοδο ParagraphFormat#getEffective. |

**Επιστρέφει:**
[ParagraphFormat](../paragraphformat)

---

### getPortions {#getPortions}

| Όνομα | Περιγραφή |
| --- | --- |
| getPortions () | Επιστρέφει τη συλλογή των τμημάτων κειμένου. Μόνο για ανάγνωση IPortionCollection. |

**Επιστρέφει:**
[PortionCollection](../portioncollection)

---

### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την κύρια παρουσίαση μιας παραγράφου. Μόνο για ανάγνωση IPresentation. |

**Επιστρέφει:**
[Presentation](../presentation)

---

### getRect {#getRect}

| Όνομα | Περιγραφή |
| --- | --- |
| getRect () | Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιορίζει την παράγραφο. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στην παράγραφο, συμπεριλαμβανομένων των κενών. |

**Επιστρέφει:**
Rectangle2D.Float

---

### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει την κύρια διαφάνεια μιας παραγράφου. Μόνο για ανάγνωση BaseSlide. |

**Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getText {#getText}

| Όνομα | Περιγραφή |
| --- | --- |
| getText () | Ανάγνωση ή εγγραφή του απλού κειμένου μιας παραγράφου. Ανάγνωση/εγγραφή String. Τιμή: Το κείμενο. |

**Επιστρέφει:**
String

---

### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Όνομα | Περιγραφή |
| --- | --- |
| joinPortionsWithSameFormatting () | Ενώνει τμηματα με την ίδια μορφοποίηση. |

**Επιστρέφει:**
void

---

### setEndParagraphPortionFormat {#setEndParagraphPortionFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndParagraphPortionFormat ([PortionFormat](../portionformat)) | Καθορίζει τις ιδιότητες του τμήματος που θα χρησιμοποιηθούν εάν ένα άλλο τμήμα εισαχθεί μετά το τελευταίο. |

**Επιστρέφει:**
void

---

### setText {#setText}

| Όνομα | Περιγραφή |
| --- | --- |
| setText (String) | Ανάγνωση ή εγγραφή του απλού κειμένου μιας παραγράφου. Ανάγνωση/εγγραφή String. Τιμή: Το κείμενο. |

**Επιστρέφει:**
void

---