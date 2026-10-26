---
title: InsertClone
second_title: Aspose.Sildes για .NET Αναφορά API
description: Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.
type: docs
weight: 120
url: /el/aspose.slides/slidecollection/insertclone/
---
## InsertClone(int, ISlide) {#insertclone}

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Index of new slide. |
| sourceSlide | ISlide | Slide to clone. |

### Τιμή Επιστροφής

Inserted slide.

### Παρατηρήσεις

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, μπορεί επίσης να κλωνοποιηθεί το master της διαφάνειας. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση των αυτόματα κλωνοποιημένων master, ώστε να αποτρέπεται η δημιουργία πολλαπλών κλώνων του ίδιου master. Η χειροκίνητη κλωνοποίηση των master διαφανειών δεν θα αποτρέπεται ούτε θα καταγράφεται. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε [`InsertClone`](../insertclone) ή [`InsertClone`](../insertclone) για κλωνοποίηση διαφανειών και [`AddClone`](../../imasterslidecollection/addclone) για κλωνοποίηση master.

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να κλωνοποιήσετε σε άλλη θέση εντός της Παρουσίασης.

```csharp
[C#]
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Κλωνοποίηση της επιθυμητής διαφάνειας στο τέλος της συλλογής διαφανειών στην ίδια παρουσίαση
    ISlideCollection slds = pres.Slides;
    // Κλωνοποίηση της επιθυμητής διαφάνειας στον καθορισμένο δείκτη στην ίδια παρουσίαση
    slds.InsertClone(2, pres.Slides[1]);
    // Αποθήκευση της τροποποιημένης παρουσίασης στο δίσκο
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να κλωνοποιήσετε σε άλλη θέση εντός της Παρουσίασης.

```csharp
[C#]
// Δημιουργία αντικειμένου Presentation για τη φόρτωση του πηγαίου αρχείου παρουσίασης
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Δημιουργία αντικειμένου Presentation για το προορισμό PPTX (όπου η διαφάνεια θα κλωνοποιηθεί)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Αποθήκευση της προοριστικής παρουσίασης στο δίσκο
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Δείτε επίσης

* διασύνδεση [ISlide](../../islide)
* κλάση [SlideCollection](../../slidecollection)
* χώρος ονομάτων [Aspose.Slides](../../slidecollection)
* συγκρότημα [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Index of new slide. |
| sourceSlide | ISlide | Slide to clone. |
| destLayout | ILayoutSlide | Layout slide for a new slide. |

### Τιμή Επιστροφής

Inserted slide.

### Δείτε επίσης

* διασύνδεση [ISlide](../../islide)
* διασύνδεση [ILayoutSlide](../../ilayoutslide)
* κλάση [SlideCollection](../../slidecollection)
* χώρος ονομάτων [Aspose.Slides](../../slidecollection)
* συγκρότημα [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Εισάγει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στη συγκεκριμένη θέση της συλλογής. Το κατάλληλο διάταγμα θα επιλεγεί αυτόματα από το καθορισμένο master (το κατάλληλο διάταγμα είναι το διάταγμα με τον ίδιο Τύπο ή Όνομα όπως το διάταγμα της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλο διάταγμα, τότε το διάταγμα της πηγής διαφάνειας θα κλωνοποιηθεί (αν η allowCloneMissingLayout είναι true) ή θα εκτοξευθεί η PptxEditException (αν η allowCloneMissingLayout είναι false).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Index of new slide. |
| sourceSlide | ISlide | Slide to clone. |
| destMaster | IMasterSlide | Master slide for a new slide. |
| allowCloneMissingLayout | Boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Τιμή Επιστροφής

Inserted slide.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |

### Δείτε επίσης

* διασύνδεση [ISlide](../../islide)
* διασύνδεση [IMasterSlide](../../imasterslide)
* κλάση [SlideCollection](../../slidecollection)
* χώρος ονομάτων [Aspose.Slides](../../slidecollection)
* συγκρότημα [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->