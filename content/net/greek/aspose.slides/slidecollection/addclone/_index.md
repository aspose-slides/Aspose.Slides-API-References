---
title: AddClone
second_title: Aspose.Sildes για .NET Αναφορά API
description: Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.
type: docs
weight: 50
url: /el/aspose.slides/slidecollection/addclone/
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

### Παρατηρήσεις

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, το master της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση των αυτόματα κλωνοποιημένων master, προκειμένου να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master slide. Η χειροκίνητη κλωνοποίηση των master slide δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε [`AddClone`](../addclone) ή [`AddClone`](../addclone) για κλωνοποίηση διαφάνειων, [`AddClone`](../../igloballayoutslidecollection/addclone) ή [`AddClone`](../../igloballayoutslidecollection/addclone) για κλωνοποίηση διατάξεων και [`AddClone`](../../imasterslidecollection/addclone) για κλωνοποίηση master.

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* κλάση [SlideCollection](../../slidecollection)
* χώρος ονομάτων [Aspose.Slides](../../slidecollection)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | ISlide | Διαφάνεια προς κλωνοποίηση. |
| section | ISection | Ενότητα για τη νέα διαφάνεια. |

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
    
    // Τώρα η δεύτερη ενότητα περιέχει ένα αντίγραφο της πρώτης διαφάνειας.
}
```

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* διεπαφή [ISection](../../isection)
* κλάση [SlideCollection](../../slidecollection)
* χώρος ονομάτων [Aspose.Slides](../../slidecollection)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | ISlide | Διαφάνεια προς κλωνοποίηση. |
| destLayout | ILayoutSlide | Διαφάνεια διάταξης για τη νέα διαφάνεια. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* διεπαφή [ILayoutSlide](../../ilayoutslide)
* κλάση [SlideCollection](../../slidecollection)
* χώρος ονομάτων [Aspose.Slides](../../slidecollection)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Προσθέτει ένα αντίγραφο μιας καθορισμένης πηγαίας διαφάνειας στο τέλος της συλλογής. Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο master (η κατάλληλη διάταξη είναι αυτή με τον ίδιο Type ή Name όπως η διάταξη της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (αν allowCloneMissingLayout είναι false).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | ISlide | Διαφάνεια προς κλωνοποίηση. |
| destMaster | IMasterSlide | Master slide για τη νέα διαφάνεια. |
| allowCloneMissingLayout | Boolean | Εάν δεν υπάρχει κατάλληλη διάταξη στο καθορισμένο master, η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (αν allowCloneMissingLayout είναι false). |

### Τιμή Επιστροφής

Νέα διαφάνεια.

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Προκαλείται εάν δεν υπάρχει κατάλληλη διάταξη στο καθορισμένο master και το allowCloneMissingLayout είναι false. |

### Δείτε επίσης

* διεπαφή [ISlide](../../islide)
* διεπαφή [IMasterSlide](../../imasterslide)
* κλάση [SlideCollection](../../slidecollection)
* χώρος ονομάτων [Aspose.Slides](../../slidecollection)
* συναρμολόγηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->