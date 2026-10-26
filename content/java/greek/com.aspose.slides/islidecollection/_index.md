---
title: ISlideCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια συλλογή διαφανειών.
type: docs
url: /el/com.aspose.slides/islidecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Αντιπροσωπεύει μια συλλογή διαφανειών.
## Μεθόδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Παίρνει το στοιχείο στη συγκεκριμένη θέση. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Προσθέτει μια καινούργια κενή διαφάνεια στο τέλος της συλλογής. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Εισάγει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Μετακινεί τη διαφάνεια από τη συλλογή στη συγκεκριμένη θέση. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Μετακινεί τις διαφάνειες από τη συλλογή στη συγκεκριμένη θέση. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Επιστρέφει έναν δείκτη της καθορισμένης διαφάνειας στη συλλογή. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Δημιουργεί διαφάνειες από το PDF αρχείο και τις προσθέτει στο τέλος της συλλογής. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Δημιουργεί διαφάνειες από το PDF αρχείο και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Δημιουργεί διαφάνειες από το PDF αρχείο και τις προσθέτει στο τέλος της συλλογής. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Δημιουργεί διαφάνειες από το PDF αρχείο και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Παίρνει το στοιχείο στη συγκεκριμένη θέση. Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση.

--------------------

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων μπορεί επίσης να κλωνοποιηθεί ο κύριος της διαφάνειας. Εσωτερικό μητρώο χρησιμοποιείται για την παρακολούθηση των αυτόματα κλωνοποιημένων κυρίων, ώστε να αποτρέπεται η δημιουργία πολλαπλών κλώνων του ίδιου κύριου. Η χειροκίνητη κλωνοποίηση των κυρίων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε #addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) ή #addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) για κλωνοποίηση διαφανειών, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) ή [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) για κλωνοποίηση διατάξεων και [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) για κλωνοποίηση κυρίων.

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Νέα διαφάνεια.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Now the second section contains a copy of the first slide.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα για τη νέα διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Νέα διαφάνεια.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση.

--------------------

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων μπορεί επίσης να κλωνοποιηθεί ο κύριος της διαφάνειας. Εσωτερικό μητρώο χρησιμοποιείται για την παρακολούθηση των αυτόματα κλωνοποιημένων κυρίων, ώστε να αποτρέπεται η δημιουργία πολλαπλών κλώνων του ίδιου κύριου. Η χειροκίνητη κλωνοποίηση των κυρίων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε #insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) ή #insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) για κλωνοποίηση διαφανειών και [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) για κλωνοποίηση κυρίων.

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Εισαχθείσα διαφάνεια.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Προσθέτει μια καινούργια κενή διαφάνεια στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διάταξη για τη διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Προστιθέμενη διαφάνεια.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διάταξη για τη διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Εισαχθείσα διαφάνεια.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διάταξη διαφάνειας για τη νέα διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Νέα διαφάνεια.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διάταξη διαφάνειας για τη νέα διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Εισαχθείσα διαφάνεια.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στο τέλος της συλλογής. Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από τον καθορισμένο κύριο (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο τύπο ή όνομα όπως η διάταξη της πηγής διαφάνειας). Αν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εξαχθεί εξαίρεση PptxEditException (αν allowCloneMissingLayout είναι false).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Κύρια διαφάνεια για τη νέα διαφάνεια. |
| allowCloneMissingLayout | boolean | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο κύριο, η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εξαχθεί εξαίρεση PptxEditException (αν allowCloneMissingLayout είναι false). |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Νέα διαφάνεια.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Εισάγει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στη συγκεκριμένη θέση της συλλογής. Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από τον καθορισμένο κύριο (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο τύπο ή όνομα όπως η διάταξη της πηγής διαφάνειας). Αν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εξαχθεί εξαίρεση PptxEditException (αν allowCloneMissingLayout είναι false).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Κύρια διαφάνεια για τη νέα διαφάνεια. |
| allowCloneMissingLayout | boolean | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο κύριο, η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εξαχθεί εξαίρεση PptxEditException (αν allowCloneMissingLayout είναι false). |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Εισαχθείσα διαφάνεια.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Η διαφάνεια που θα αφαιρεθεί από τη συλλογή. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου που θα αφαιρεθεί. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες.

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Πίνακας των [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης της πρώτης διαφάνειας προς προσθήκη. |
| count | int | Αριθμός διαφανειών προς προσθήκη. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Πίνακας των [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Μετακινεί τη διαφάνεια από τη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης προορισμού. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς μετακίνηση. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Μετακινεί τις διαφάνειες από τη συλλογή στη συγκεκριμένη θέση. Οι διαφάνειες θα τοποθετηθούν ξεκινώντας από τον δείκτη με τη σειρά που εμφανίζονται στη λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης προορισμού. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Διαφάνειες προς μετακίνηση. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Επιστρέφει έναν δείκτη της καθορισμένης διαφάνειας στη συλλογή.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς εύρεση. |

**Επιστρέφει:**
int - Δείκτης μιας διαφάνειας ή -1 αν η διαφάνεια δεν ανήκει σε αυτή τη συλλογή.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Δημιουργεί διαφάνειες από το PDF αρχείο και τις προσθέτει στο τέλος της συλλογής.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Ένα μονοπάτι προς το έγγραφο PDF |

**Επιστρέφει:**  
com.aspose.slides.ISlide[] - Προστέθηκαν διαφάνειες  
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής PDF.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Ένα μονοπάτι προς το έγγραφο PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Επιλογές εισαγωγής PDF |

**Επιστρέφει:**  
com.aspose.slides.ISlide[] - Προστέθηκαν διαφάνειες  
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Μια ροή που θα χρησιμοποιηθεί ως πηγή του εγγράφου PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Επιλογές εισαγωγής PDF |

**Επιστρέφει:**  
com.aspose.slides.ISlide[] - Προστέθηκαν διαφάνειες  
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Μια ροή που θα χρησιμοποιηθεί ως πηγή του εγγράφου PDF |

**Επιστρέφει:**  
com.aspose.slides.ISlide[] - Προστέθηκαν διαφάνειες  
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών πόρων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**  
com.aspose.slides.ISlide[] - Προστέθηκαν διαφάνειες.  
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | java.lang.String | HTML προς προσθήκη. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες  
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών πόρων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες.  
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες  
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών πόρων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες.  
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες  
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών πόρων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες.  
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες  
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες  
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών πόρων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες.  
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες  
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών πόρων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**  
com.aspose.slides.ISSlide[] - Προστέθηκαν διαφάνειες.