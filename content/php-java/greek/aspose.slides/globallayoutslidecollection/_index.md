---
title: GlobalLayoutSlideCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection κλάση

Αναπαριστά μια συλλογή όλων των διαφανειών διάταξης στην παρουσίαση.  
Επεκτείνει την κλάση LayoutSlideCollection με μεθόδους για προσθήκη/κλωνοποίηση διαφανειών διάταξης στο πλαίσιο της ενοποίησης των μεμονωμένων συλλογών των διαφανειών διάταξης του master.

### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add ([MasterSlide](../masterslide), byte, String) | Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| master | [MasterSlide](../masterslide) | Master διαφάνεια για τη νέα διάταξη. |
| layoutType | byte | Τύπος διάταξης για τη νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Όνομα για τη νέα διάταξη. Εάν το όνομα που δόθηκε είναι ήδη σε χρήση, θα προκληθεί ArgumentException. Εάν περάσει τιμή null, το όνομα δημιουργείται αυτόματα βάσει του τύπου διάταξης (π.χ. «Title Slide» ή «1_Title Slide», «2_..», κ.λπ.). 1) Η προσθήκη διάταξης για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει placeholders ούτε σχήματα. 2) Αντίστοιχο της μεθόδου είναι η μέθοδος IMasterLayoutSlideCollection#add(byte,String) που προσπελάζεται μέσω της ιδιότητας ( IMasterSlide#getLayoutSlides). |

**Τιμές Επιστροφής:**  
[LayoutSlide](../layoutslide)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Προκαλείται εάν η τιμή του layoutName είναι ήδη σε χρήση στη συλλογή των διαφανειών διάταξης του master. |


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide)) | Προσθέτει ένα αντίγραφο της καθορισμένης διαφάνειας διάταξης στην παρουσίαση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | Διαφάνεια προς κλωνοποίηση. Κατά την κλωνοποίηση μιας διάταξης μεταξύ διαφορετικών παρουσιάσεων, μπορεί να κλωνοποιηθεί και το master της διάταξης ώστε να διατηρηθεί η μορφοποίηση της πηγής. Εσωτερικό μητρώο χρησιμοποιείται για την αυτόματη παρακολούθηση κλωνοποιημένων masters ώστε να αποτραπεί η δημιουργία πολλαπλών αντιγράφων του ίδιου master. Η χειροκίνητη κλωνοποίηση master διαφανειών δεν θα προληφθεί ούτε θα καταγραφεί. |

**Τιμές Επιστροφής:**  
[LayoutSlide](../layoutslide)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide), [MasterSlide](../masterslide)) | Προσθέτει ένα αντίγραφο της καθορισμένης διαφάνειας διάταξης στην παρουσίαση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [MasterSlide](../masterslide) | Master διαφάνεια για τη νέα διάταξη. 1) Η νέα διάταξη θα συνδεθεί με το ορισμένο master στην προοριστική παρουσίαση. Αυτό αντιστοιχεί στη λειτουργία αντιγραφής/επικόλλησης με την επιλογή «Use Destination Theme» στο PowerPoint. 2) Αντίστοιχο της μεθόδου είναι η μέθοδος IMasterLayoutSlideCollection#addClone(ILayoutSlide) που προσπελάζεται μέσω της ιδιότητας ( IMasterSlide#getLayoutSlides). |

**Τιμές Επιστροφής:**  
[LayoutSlide](../layoutslide)


---