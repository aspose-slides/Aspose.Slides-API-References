---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά μια συλλογή όλων των διαφανειών διάταξης του ορισμένου κύριου πρότυπου.
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

Αναπαριστά μια συλλογή όλων των διαφανειών διάταξης του ορισμένου κύριου πρότυπου. Επεκτείνει την κλάση LayoutSlideCollection με μεθόδους για προσθήκη/ενσωμάτωση/αφαίρεση/κλωνοποίηση/αναδιάταξη διαφανειών διάταξης στο πλαίσιο των ατομικών συλλογών των διαφανειών διάταξης του κύριου πρότυπου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διάταξης διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Εισάγει ένα αντίγραφο μιας καθορισμένης διάταξης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Προσθέτει μια νέα διάταξη διαφάνειας στο τέλος της συλλογής. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Εισάγει μια νέα διάταξη διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Μετακινεί τη διάταξη διαφάνειας από τη συλλογή στη συγκεκριμένη θέση. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διάταξης διαφάνειας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

1) Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ανάλογο της λειτουργίας αντιγραφή/επικόλληση με την επιλογή "Use Destination Theme" στο PowerPoint. 2) Ανάλογη αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) που προσπελαύνεται μέσω της ιδιότητας ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Διαφάνεια που προστέθηκε.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Εισάγει ένα αντίγραφο μιας καθορισμένης διάταξης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ανάλογο της λειτουργίας αντιγραφή/επικόλληση με την επιλογή "Use Destination Theme" στο PowerPoint.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Διαφάνεια που εισήχθη.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Προσθέτει μια νέα διάταξη διαφάνειας στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα εξαχθεί ArgumentException. Εάν παρασχεθεί παράμετρος null, τότε το όνομα θα δημιουργείται αυτόματα σύμφωνα με τον δοσμένο τύπο διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

--------------------

1) Η προστεθείσα διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει καθοριστικές θέσεις και δεν έχει σχήματα. 2) Ανάλογη αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) που προσπελαύνεται μέσω της ιδιότητας ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Διαφάνεια που προστέθηκε.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Εισάγει μια νέα διάταξη διαφάνειας στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα εξαχθεί ArgumentException. Εάν παρασχεθεί παράμετρος null, τότε το όνομα θα δημιουργείται αυτόματα σύμφωνα με τον δοσμένο τύπο διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

--------------------

Η εισαχθείσα διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει καθοριστικές θέσεις και δεν έχει σχήματα.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Διαφάνεια που εισήχθη.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του στοιχείου που θα αφαιρεθεί. |

--------------------

1) Για να αποφευχθεί η εξαίρεση PptxEditException, ελέγξτε πρώτα την ιδιότητα HasDependingSlides της διάταξης. 2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) για να απλοποιήσετε τον κώδικα.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Μετακινεί τη διάταξη διαφάνειας από τη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης προορισμού. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς μετακίνηση. |