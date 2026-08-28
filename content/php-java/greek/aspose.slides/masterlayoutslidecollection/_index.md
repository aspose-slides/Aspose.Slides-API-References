---
title: MasterLayoutSlideCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection κλάση

Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης του καθορισμένου κύριου διαφάνειας.  
Επεκτείνει την κλάση LayoutSlideCollection με μεθόδους για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση/αναδιάταξη διαφανειών διάταξης στο πλαίσιο των μεμονωμένων συλλογών των διαφανειών διάταξης του κύριου διαφάνειας.

### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (byte, String) | Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτήν τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Όνομα για μια νέα διάταξη. Εάν το παρεχόμενο όνομα είναι ήδη σε χρήση, θα εξαχθεί ArgumentException. Εάν δοθεί παράμετρος null, το όνομα θα δημιουργηθεί αυτόματα βάσει του παρεχόμενου τύπου διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κλπ.). 1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει placeholders και σχήματα. 2) Αναλογική της μεθόδου είναι η μέθοδος IGlobalLayoutSlideCollection#add(IMasterSlide,byte,String) η οποία προσπελάζεται μέσω της ιδιότητας ( IPresentation#getLayoutSlides). |

**Επιστρέφει:**
[LayoutSlide](../layoutslide)

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Εξαίρεση εάν η τιμή του ονόματος διάταξης layoutName είναι ήδη σε χρήση σε αυτή τη συλλογή των διατάξεων. |


---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide)) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | Διαφάνεια προς κλωνοποίηση. 1) Η νέα διάταξη θα συνδεθεί με τον γονικό κύριο διαφάνειας για αυτή τη συλλογή διαφανειών διάταξης. Έτσι αποτελεί την αναλογική του copy/paste με την επιλογή "Use Destination Theme" στο PowerPoint. 2) Αναλογική της μεθόδου είναι η μέθοδος IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) η οποία προσπελάζεται μέσω της ιδιότητας ( IPresentation#getLayoutSlides). |

**Επιστρέφει:**
[LayoutSlide](../layoutslide)

---

### insert {#insert}

| Όνομα | Περιγραφή |
| --- | --- |
| insert (int, byte, String) | Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτήν τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Όνομα για μια νέα διάταξη. Εάν το παρεχόμενο όνομα είναι ήδη σε χρήση, θα εξαχθεί ArgumentException. Εάν δοθεί παράμετρος null, το όνομα θα δημιουργηθεί αυτόματα βάσει του παρεχόμενου τύπου διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κλπ.). Η εισαχθείσα διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει placeholders και σχήματα. |

**Επιστρέφει:**
[LayoutSlide](../layoutslide)

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Εξαίρεση εάν η τιμή του ονόματος διάταξης layoutName είναι ήδη σε χρήση σε αυτή τη συλλογή των διατάξεων. |

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [LayoutSlide](../layoutslide)) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στη συγκεκριμένη θέση της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceLayout | [LayoutSlide](../layoutslide) | Διαφάνεια προς κλωνοποίηση. Η νέα διάταξη θα συνδεθεί με τον γονικό κύριο διαφάνειας για αυτή τη συλλογή διαφανειών διάταξης. |

**Επιστρέφει:**
[LayoutSlide](../layoutslide)

---

### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Απομακρύνει το στοιχείο στη συγκεκριμένη θέση της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα αφαιρεθεί. 1) Για να αποφευχθεί η εξαίρεση PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides του layout πριν. 2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο ILayoutSlide#remove για απλούστερο κώδικα. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| PptxEditException | Εξαίρεση εάν η διάταξη χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides είναι true). |

---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [LayoutSlide](../layoutslide)) | Μετακινεί τη διαφάνεια διάταξης από τη συλλογή στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στόχου. |
| layoutSlide | [LayoutSlide](../layoutslide) | Διαφάνεια προς μετακίνηση. |

**Επιστρέφει:**
void

---