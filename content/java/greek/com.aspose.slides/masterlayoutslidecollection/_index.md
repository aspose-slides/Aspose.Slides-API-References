---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides για την αναφορά API Java
description: Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης του καθορισμένου master slide.
type: docs
url: /el/com.aspose.slides/masterlayoutslidecollection/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης του ορισμένου master slide. Επεκτείνει την κλάση LayoutSlideCollection με μεθόδους για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση/αναδιάταξη διαφανειών διάταξης στο πλαίσιο των μεμονωμένων συλλογών των διαφανειών διάταξης του master.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στο τέλος της συλλογής. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην καθορισμένη θέση της συλλογής. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Εισάγει μια νέα διαφάνεια διάταξης στην καθορισμένη θέση της συλλογής. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στην καθορισμένη θέση της συλλογής. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Μετακινεί τη διαφάνεια διάταξης από τη συλλογή στην καθορισμένη θέση. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

1) Η νέα διάταξη θα συνδεθεί με το γονικό master slide για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ανάλωση της λειτουργίας αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint. 2) Ανάλωση αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) που προσπελάζεται με την ιδιότητα ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).  

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστιθέμενη διαφάνεια.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην καθορισμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

Η νέα διάταξη θα συνδεθεί με το γονικό master slide για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ανάλωση της λειτουργίας αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint.  

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Εισαχθείσα διαφάνεια.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Αν το παρεχόμενο όνομα είναι ήδη σε χρήση, θα εξαχθεί ArgumentException. Αν περαστεί null, τότε το όνομα θα δημιουργηθεί αυτόματα βάσει του παρεχόμενου τύπου διάταξης (π.χ. "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

--------------------

1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει placeholders και σχήματα. 2) Ανάλωση αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) που προσπελάζεται με την ιδιότητα ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).  

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστιθέμενη διαφάνεια.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Εισάγει μια νέα διαφάνεια διάταξης στην καθορισμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Αν το παρεχόμενο όνομα είναι ήδη σε χρήση, θα εξαχθεί ArgumentException. Αν περαστεί null, τότε το όνομα θα δημιουργηθεί αυτόματα βάσει του παρεχόμενου τύπου διάταξης (π.χ. "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

--------------------

Η εισαχθείσα διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει placeholders και σχήματα.  

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Εισαχθείσα διαφάνεια.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στην καθορισμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου προς αφαίρεση. |

--------------------

1) Για να αποφευχθεί η εξαίρεση PptxEditException, ελέγξτε πρώτα την ιδιότητα HasDependingSlides της διάταξης. 2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) για απλοποίηση του κώδικα.  

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Μετακινεί τη διαφάνεια διάταξης από τη συλλογή στην καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Στόχος δείκτης. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς μετακίνηση. |