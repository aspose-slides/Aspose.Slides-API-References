---
title: SlideCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεί μια συλλογή διαφανειών.
type: docs
url: /el/com.aspose.slides/slidecollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Αντιπροσωπεί μια συλλογή διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της καθορισμένης ενότητας. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Προσθέτει μια νέα κενή διαφάνεια στο τέλος της συλλογής. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης πηγαίας διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης πηγαίας διαφάνειας στη καθορισμένη θέση της συλλογής. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμοδείκτη που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java αριθμοδείκτη για ολόκληρη τη συλλογή. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Μετακινεί τη διαφάνεια από τη συλλογή στη καθορισμένη θέση. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Μετακινεί τις διαφάνειες από τη συλλογή στη καθορισμένη θέση. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Επιστρέφει το δείκτη της καθορισμένης διαφάνειας στη συλλογή. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής pdf. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ανθεκτική σε νήματα). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |

### size() {#size--}
```
public final int size()
```

Λαμβάνει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο-ανάγνωση [Slide](../../com.aspose.slides/slide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, η κύρια διαφάνεια της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Ένα εσωτερικό μητρώο χρησιμοποιείται για την παρακολούθηση αυτόματα κλωνοποιημένων κύριων διαφανειών, ώστε να αποτραπεί η δημιουργία πολλαπλών κλωνοποιήσεων της ίδιας κύριας διαφάνειας. Η χειροκίνητη κλωνοποίηση των κύριων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε περισσότερο έλεγχο στη διαδικασία κλωνοποίησης, χρησιμοποιήστε \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) ή \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) για κλωνοποίηση διαφανειών, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) ή [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) για κλωνοποίηση διατάξεων και [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) για κλωνοποίηση κύριων διαφανειών.

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Νέα διαφάνεια.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της καθορισμένης ενότητας.

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
>      // Τώρα η δεύτερη ενότητα περιέχει ένα αντίγραφο της πρώτης διαφάνειας.
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
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Δημιουργήστε Presentation κλάση που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Κλωνοποιήστε τη ζητούμενη διαφάνεια στο τέλος της συλλογής διαφανειών στην ίδια παρουσίαση
>      ISlideCollection slds = pres.getSlides();
>      // Κλωνοποιήστε τη ζητούμενη διαφάνεια στο καθορισμένο δείκτη στην ίδια παρουσίαση
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Γράψτε την τροποποιημένη παρουσίαση στο δίσκο
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Δημιουργήστε Presentation κλάση για τη φόρτωση του αρχικού αρχείου παρουσίασης
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Δημιουργήστε Presentation κλάση για το προορισμό PPTX (όπου η διαφάνεια θα κλωνοποιηθεί)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Γράψτε την προορισμένη παρουσίαση στο δίσκο
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, η κύρια διαφάνεια της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Ένα εσωτερικό μητρώο χρησιμοποιείται για την παρακολούθηση αυτόματα κλωνοποιημένων κύριων διαφανειών, ώστε να αποτραπεί η δημιουργία πολλαπλών κλωνοποιήσεων της ίδιας κύριας διαφάνειας. Η χειροκίνητη κλωνοποίηση των κύριων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε περισσότερο έλεγχο στη διαδικασία κλωνοποίησης, χρησιμοποιήστε \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) ή \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) για κλωνοποίηση διαφανειών και [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) για κλωνοποίηση κύριων διαφανειών.

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Εισαχθείσα διαφάνεια.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Προσθέτει μια νέα κενή διαφάνεια στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διάταξη για μια διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Προστέθηκε διαφάνεια.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας νέας διαφάνειας. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διάταξη για μια διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Εισαχθείσα διαφάνεια.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διάταξη διαφάνειας για τη νέα διαφάνεια. |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Νέα διαφάνεια.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη καθορισμένη θέση της συλλογής.

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
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης πηγαίας διαφάνειας στο τέλος της συλλογής. Θα επιλεγεί αυτόματα η κατάλληλη διάταξη από τον καθορισμένο κύριο (η κατάλληλη διάταξη είναι αυτή που έχει τον ίδιο Type ή Name με τη διάταξη της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εκδοθεί PptxEditException (αν allowCloneMissingLayout είναι false).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Κύρια διαφάνεια για τη νέα διαφάνεια. |
| allowCloneMissingLayout | boolean | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο κύριο, η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εκδοθεί PptxEditException (αν allowCloneMissingLayout είναι false). |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Νέα διαφάνεια.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Εισάγει ένα αντίγραφο μιας συγκεκριμένης πηγαίας διαφάνειας στη καθορισμένη θέση της συλλογής. Θα επιλεγεί αυτόματα η κατάλληλη διάταξη από τον καθορισμένο κύριο (η κατάλληλη διάταξη είναι αυτή που έχει τον ίδιο Type ή Name με τη διάταξη της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εκδοθεί PptxEditException (αν allowCloneMissingLayout είναι false).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Κύρια διαφάνεια για τη νέα διαφάνεια. |
| allowCloneMissingLayout | boolean | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο κύριο, η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εκδοθεί PptxEditException (αν allowCloneMissingLayout είναι false). |

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide) - Εισαχθείσα διαφάνεια.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Η διαφάνεια που πρέπει να αφαιρεθεί από τη συλλογή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου που θα αφαιρεθεί. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Επιστρέφει έναν αριθμοδείκτη που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Επιστρέφει έναν java αριθμοδείκτη για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες.

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης της πρώτης διαφάνειας για προσθήκη. |
| count | int | Αριθμός διαφανειών για προσθήκη. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Μετακινεί τη διαφάνεια από τη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης προορισμού. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς μετακίνηση. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Μετακινεί τις διαφάνειες από τη συλλογή στη καθορισμένη θέση. Οι διαφάνειες θα τοποθετηθούν αρχίζοντας από το δείκτη, στη σειρά που εμφανίζονται στη λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης προορισμού. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Διαφάνειες προς μετακίνηση. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Επιστρέφει το δείκτη της καθορισμένης διαφάνειας στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια προς εύρεση. |

**Επιστρέφει:**
int - Δείκτης μιας διαφάνειας ή -1 εάν η διαφάνεια δεν προέρχεται από αυτή τη συλλογή.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής.

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
| path | java.lang.String | Διαδρομή προς το έγγραφο PDF |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής pdf.

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
| path | java.lang.String | Διαδρομή προς το έγγραφο PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Επιλογές εισαγωγής pdf |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
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
| pdfStream | java.io.InputStream | Ροή η οποία θα χρησιμοποιηθεί ως πηγή του εγγράφου PDF |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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
| pdfStream | java.io.InputStream | Ροή η οποία θα χρησιμοποιηθεί ως πηγή του εγγράφου PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Επιλογές εισαγωγής pdf |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | java.lang.String | HTML προς προσθήκη. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

--------------------

> ```
> // Δημιουργήστε μια παρουσίαση της κλάσης Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Καλέστε τη μέθοδο AddFromHtml και περάστε το αρχείο HTML.
>          pres.getSlides().addFromHtml(fos);
>          // Χρησιμοποιήστε τη μέθοδο Save για να αποθηκεύσετε το αρχείο ως έγγραφο PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlText | java.lang.String | HTML προς προσθήκη. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | java.lang.String | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση εισαγωγής. |
| htmlStream | java.io.InputStream | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| useSlideWithIndexAsStart | boolean | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Διαφάνειες που προστέθηκαν

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας-στόχος. |
| index | int | Αρχικός δείκτης στον πίνακα-στόχο. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ανθεκτική σε νήματα). Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο-ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object