---
title: AddClone
second_title: Aspose.Sildes για .NET Αναφορά API
description: Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.
type: docs
weight: 20
url: /el/aspose.slides/islidecollection/addclone/
---
## AddClone(ISlide) {#addclone}

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | ISlide | Διαφάνεια προς κλωνοποίηση. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

### Σχόλια

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, μπορεί επίσης να κλωνοποιηθεί ο master της διαφάνειας. Ένα εσωτερικό μητρώο χρησιμοποιείται για την παρακολούθηση των αυτόματα κλωνοποιημένων master ώστε να αποτραπεί η δημιουργία πολλαπλών αντιγράφων του ίδιου master. Η χειροκίνητη κλωνοποίηση των master διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε [`AddClone`](../addclone) ή [`AddClone`](../addclone) για κλωνοποίηση διαφανειών, [`AddClone`](../../igloballayoutslidecollection/addclone) ή [`AddClone`](../../igloballayoutslidecollection/addclone) για κλωνοποίηση διατάξεων και [`AddClone`](../../imasterslidecollection/addclone) για κλωνοποίηση master.

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* διεπαφή [ISlideCollection](../../islidecollection)
* χώρος ονομάτων [Aspose.Slides](../../islidecollection)
* συγκρότηση [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος του καθορισμένου τμήματος.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | ISlide | Διαφάνεια προς κλωνοποίηση. |
| section | ISection | Τμήμα για τη νέα διαφάνεια. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentNullException |  |
| [PptxEditException](../../pptxeditexception) |  |

### Παραδείγματα

```csharp
[C#]
using (IPresentation presentation = new Presentation())
{
    presentation.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    presentation.Sections.AddSection("Section 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Section 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Τώρα το δεύτερο τμήμα περιέχει ένα αντίγραφο της πρώτης διαφάνειας.
}
```

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* διεπαφή [ISection](../../isection)
* διεπαφή [ISlideCollection](../../islidecollection)
* χώρος ονομάτων [Aspose.Slides](../../islidecollection)
* συγκρότηση [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | ISlide | Διαφάνεια προς κλωνοποίηση. |
| destLayout | ILayoutSlide | Διάταξη διαφάνειας για τη νέα διαφάνεια. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* διεπαφή [ILayoutSlide](../../ilayoutslide)
* διεπαφή [ISlideCollection](../../islidecollection)
* χώρος ονομάτων [Aspose.Slides](../../islidecollection)
* συγκρότηση [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας πηγής στο τέλος της συλλογής. Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από τον καθορισμένο master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Τύπο ή Όνομα όπως η διάταξη της διαφάνειας πηγής). Εάν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της διαφάνειας πηγής θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή θα εκτοξευθεί η εξαίρεση PptxEditException (εάν το allowCloneMissingLayout είναι false).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | ISlide | Διαφάνεια προς κλωνοποίηση. |
| destMaster | IMasterSlide | Master διαφάνειας για τη νέα διαφάνεια. |
| allowCloneMissingLayout | Boolean | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο master, τότε η διάταξη της διαφάνειας πηγής θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή θα εκτοξευθεί η εξαίρεση PptxEditException (εάν το allowCloneMissingLayout είναι false). |

### Τιμή Επιστροφής

Νέα διαφάνεια.

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Γίνεται ρίψη εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο master και το allowCloneMissingLayout είναι false. |

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* διεπαφή [IMasterSlide](../../imasterslide)
* διεπαφή [ISlideCollection](../../islidecollection)
* χώρος ονομάτων [Aspose.Slides](../../islidecollection)
* συγκρότηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->