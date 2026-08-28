---
title: SlideCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/slidecollection/
---
## SlideCollection κλάση

Αναπαριστά μια συλλογή διαφανειών.

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Slide](../slide)) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Διαφάνεια προς κλωνοποίηση. Όταν κλωνοποιείται μια διαφάνεια μεταξύ διαφορετικών παρουσιάσεων, το master της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Η εσωτερική μητρώα χρησιμοποιείται για την παρακολούθηση των αυτόματα κλωνοποιημένων masters ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων της ίδιας master διαφάνειας. Η χειροκίνητη κλωνοποίηση master διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε #addClone(ISlide,ILayoutSlide) ή #addClone(ISlide,IMasterSlide,boolean) για κλωνοποίηση διαφανειών, IGlobalLayoutSlideCollection#addClone(ILayoutSlide) ή IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) για κλωνοποίηση διατάξεων και IMasterSlideCollection#addClone(IMasterSlide) για κλωνοποίηση masters. |

**Επιστρέφει:**
[Slide](../slide)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Slide](../slide), [Section](../section)) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Διαφάνεια προς κλωνοποίηση. |
| section | [Section](../section) | section για τη νέα διαφάνεια. |

**Επιστρέφει:**
[Slide](../slide)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Όταν η παράμετρος section περιέχει λανθασμένη ή μη έγκυρη τιμή. |

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Slide](../slide), [LayoutSlide](../layoutslide)) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Διαφάνεια προς κλωνοποίηση. |
| destLayout | [LayoutSlide](../layoutslide) | Layout διαφάνειας για τη νέα διαφάνεια. |

**Επιστρέφει:**
[Slide](../slide)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Slide](../slide), [MasterSlide](../masterslide), boolean) | Προσθέτει ένα αντίγραφο μιας καθορισμένης πηγαίας διαφάνειας στο τέλος της συλλογής. Η κατάλληλη διαγραφή θα επιλεχθεί αυτόματα από το καθορισμένο master (η κατάλληλη διαγραφή είναι η διαγραφή με τον ίδιο Type ή Name όπως η διαγραφή της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διαγραφή, η διαγραφή της πηγαίας διαφάνειας θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή θα εκτοξευθεί PptxEditException (εάν το allowCloneMissingLayout είναι false). |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [MasterSlide](../masterslide) | Master διαφάνειας για τη νέα διαφάνεια. |
| allowCloneMissingLayout | boolean | Εάν δεν υπάρχει κατάλληλη διαγραφή στο καθορισμένο master, η διαγραφή της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εκτοξευθεί PptxEditException (αν allowCloneMissingLayout είναι false). |

**Επιστρέφει:**
[Slide](../slide)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Εκτοξεύεται εάν δεν υπάρχει κατάλληλη διαγραφή στο καθορισμένο master και το allowCloneMissingLayout είναι false. |

---

### addEmptySlide {#addEmptySlide}

| Όνομα | Περιγραφή |
| --- | --- |
| addEmptySlide ([LayoutSlide](../layoutslide)) | Προσθέτει μια νέα κενή διαφάνεια στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| layout | [LayoutSlide](../layoutslide) | Layout για τη διαφάνεια. |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | String | HTML προς προσθήκη. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | String | HTML προς προσθήκη. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | String | HTML προς προσθήκη. |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | InputStream | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή αρχείου HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | InputStream | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή αρχείου HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromHtml (InputStream) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | InputStream | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή αρχείου HTML. |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromPdf (String) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Διαδρομή προς το έγγραφο PDF |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromPdf (String, [PdfImportOptions](../pdfimportoptions)) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής pdf. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Διαδρομή προς το έγγραφο PDF |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | Επιλογές για εισαγωγή pdf |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromPdf (InputStream) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pdfStream | InputStream | Ροή που θα χρησιμοποιηθεί ως πηγή του εγγράφου PDF |

**Επιστρέφει:**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| addFromPdf (InputStream, [PdfImportOptions](../pdfimportoptions)) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pdfStream | InputStream | Ροή που θα χρησιμοποιηθεί ως πηγή του εγγράφου PDF |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | Επιλογές για εισαγωγή pdf |

**Επιστρέφει:**
[Slide](../slide)

---

### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Επιστρέφει μια ρίζα συγχρονισμού. Αντικείμενο μόνο για ανάγνωση. |

**Επιστρέφει:**
Object

---

### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Παίρνει το στοιχείο στον καθορισμένο δείκτη. Slide μόνο για ανάγνωση. |

**Επιστρέφει:**
[Slide](../slide)

---

### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([Slide](../slide)) | Επιστρέφει έναν δείκτη της καθορισμένης διαφάνειας στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [Slide](../slide) | Διαφάνεια προς εύρεση. |

**Επιστρέφει:**
int

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Slide](../slide)) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [Slide](../slide) | Διαφάνεια προς κλωνοποίηση. Όταν κλωνοποιείται μια διαφάνεια μεταξύ διαφορετικών παρουσιάσεων, το master της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Η εσωτερική μητρώα χρησιμοποιείται για την παρακολούθηση των αυτόματα κλωνοποιημένων masters ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων της ίδιας master διαφάνειας. Η χειροκίνητη κλωνοποίηση master διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε #insertClone(int,ISlide,ILayoutSlide) ή #insertClone(int,ISlide,IMasterSlide,boolean) για κλωνοποίηση διαφανειών και IMasterSlideCollection#addClone(IMasterSlide) για κλωνοποίηση masters. |

**Επιστρέφει:**
[Slide](../slide)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Slide](../slide), [LayoutSlide](../layoutslide)) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [Slide](../slide) | Διαφάνεια προς κλωνοποίηση. |
| destLayout | [LayoutSlide](../layoutslide) | Layout διαφάνειας για τη νέα διαφάνεια. |

**Επιστρέφει:**
[Slide](../slide)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Slide](../slide), [MasterSlide](../masterslide), boolean) | Εισάγει ένα αντίγραφο μιας καθορισμένης πηγαίας διαφάνειας στη καθορισμένη θέση της συλλογής. Η κατάλληλη διαγραφή θα επιλεχθεί αυτόματα από το καθορισμένο master (η κατάλληλη διαγραφή είναι η διαγραφή με τον ίδιο Type ή Name όπως η διαγραφή της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διαγραφή, η διαγραφή της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εκτοξευθεί PptxEditException (αν allowCloneMissingLayout είναι false). |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [Slide](../slide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [MasterSlide](../masterslide) | Master διαφάνειας για τη νέα διαφάνεια. |
| allowCloneMissingLayout | boolean | Εάν δεν υπάρχει κατάλληλη διαγραφή στο καθορισμένο master, η διαγραφή της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εκτοξευθεί PptxEditException (αν allowCloneMissingLayout είναι false). |

**Επιστρέφει:**
[Slide](../slide)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Εκτοξεύεται εάν δεν υπάρχει κατάλληλη διαγραφή στο καθορισμένο master και το allowCloneMissingLayout είναι false. |

---

### insertEmptySlide {#insertEmptySlide}

| Όνομα | Περιγραφή |
| --- | --- |
| insertEmptySlide (int, [LayoutSlide](../layoutslide)) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| layout | [LayoutSlide](../layoutslide) | Layout για τη διαφάνεια. |

**Επιστρέφει:**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| Όνομα | Περιγραφή |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | String | HTML προς προσθήκη. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlText | String | Html προς προσθήκη. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String, boolean) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlText | String | Html προς προσθήκη. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι true, η εισαγωγή δεδομένων θα ξεκινήσει από ένα κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι false, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String, boolean) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlText | String | Html προς προσθήκη. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι true, η εισαγωγή δεδομένων θα ξεκινήσει από ένα κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι false, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlText | String | Html προς προσθήκη. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, boolean) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlText | String | Html προς προσθήκη. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι true, η εισαγωγή δεδομένων θα ξεκινήσει από ένα κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι false, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlStream | InputStream | Ένα αντικείμενο Stream το οποίο θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlStream | InputStream | Ένα αντικείμενο Stream το οποίο θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [HtmlExternalResolver](../htmlexternalresolver), String, boolean) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlStream | InputStream | Ένα αντικείμενο Stream το οποίο θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι true, η εισαγωγή δεδομένων θα ξεκινήσει από ένα κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι false, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [ExternalResourceResolver](../externalresourceresolver), String, boolean) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlStream | InputStream | Ένα αντικείμενο Stream το οποίο θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι true, η εισαγωγή δεδομένων θα ξεκινήσει από ένα κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι false, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, InputStream) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlStream | InputStream | Ένα αντικείμενο Stream το οποίο θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

**Επιστρέφει:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, InputStream, boolean) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση για εισαγωγή. |
| htmlStream | InputStream | Ένα αντικείμενο Stream το οποίο θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι true, η εισαγωγή δεδομένων θα ξεκινήσει από ένα κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν είναι false, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
[Slide](../slide)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean. |

**Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |

**Επιστρέφει:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

**Επιστρέφει:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Slide](../slide)) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Slide](../slide) | Η διαφάνεια που πρέπει να αφαιρεθεί από τη συλλογή. |

**Επιστρέφει:**
void


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μηδενικής βάσης του στοιχείου προς αφαίρεση. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | Όταν η παράμετρος index περιέχει λανθασμένο αριθμό ενότητας. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Slide](../slide)) | Μετακινεί τη διαφάνεια από τη συλλογή στην καθορισμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης προορισμού. |
| slide | [Slide](../slide) | Διαφάνεια προς μετακίνηση. |

**Επιστρέφει:**
void


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, com.aspose.slides.ISlide[]) | Μετακινεί διαφάνειες από τη συλλογή στην καθορισμένη θέση. Οι διαφάνειες θα τοποθετηθούν ξεκινώντας από τον δείκτη, με τη σειρά που εμφανίζονται στη λίστα. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης προορισμού. |
| slides | com.aspose.slides.ISlide[] | Διαφάνειες προς μετακίνηση. |

**Επιστρέφει:**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πρακτικά στη συλλογή. Μόνο για ανάγνωση int. |

**Επιστρέφει:**
int


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray () | Δημιουργεί και επιστρέφει ένα πίνακα με όλες τις διαφάνειες. |

**Επιστρέφει:**
[Slide](../slide)


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray (int, int) | Δημιουργεί και επιστρέφει ένα πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης της πρώτης διαφάνειας προς προσθήκη. |
| count | int | Αριθμός διαφανειών προς προσθήκη. |

**Επιστρέφει:**
[Slide](../slide)


---