---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης του καθορισμένου κύριου σλάιντ.
type: docs
url: /el/com.aspose.slides/imasterlayoutslidecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης του καθορισμένου κύριου σλάιντ. Επεκτείνει τη διεπαφή ILayoutSlideCollection με μεθόδους για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης στο πλαίσιο των ατομικών συλλογών των διαφανειών διάταξης του κύριου σλάιντ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στο τέλος της συλλογής. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στη συγκεκριμένη θέση της συλλογής. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής. |
| [removeAt(int index)](#removeAt-int-) | Καταργεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Μετακινεί τη διαφάνεια διάταξης από τη συλλογή στη συγκεκριμένη θέση. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση.

--------------------

1) Η νέα διάταξη θα συνδεθεί με τον γονικό κύριο σλάιντ για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ανάλογο της λειτουργίας αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint. 2) Η ανάλογη μέθοδος είναι η μέθοδος [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) που προσπελαύνεται μέσω της ιδιότητας [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση.

--------------------

Η νέα διάταξη θα συνδεθεί με τον γονικό κύριο σλάιντ για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ανάλογο της λειτουργίας αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Εισαγόμενη διαφάνεια.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Εάν το όνομα που δίνεται είναι ήδη σε χρήση, θα εκτιναχθεί το ArgumentException. Εάν περαστεί παράμετρος null, τότε το όνομα θα δημιουργηθεί αυτόματα με βάση τον τύπο διάταξης που δόθηκε (π.χ. "Title Slide" ή "1_Title Slide", "2_..", κλπ). |

--------------------

1) Προστέθηκε διάταξη για την τιμή SlideLayoutType.Custom του layoutType που δεν περιέχει placeholders και δεν έχει σχήματα. 2) Η ανάλογη μέθοδος είναι η μέθοδος [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) που προσπελαύνεται μέσω της ιδιότητας [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Εάν το όνομα που δίνεται είναι ήδη σε χρήση, θα εκτιναχθεί το ArgumentException. Εάν περαστεί παράμετρος null, τότε το όνομα θα δημιουργηθεί αυτόματα με βάση τον τύπο διάταξης που δόθηκε (π.χ. "Title Slide" ή "1_Title Slide", "2_..", κλπ). |

--------------------

Η εισαγόμενη διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει placeholders και δεν έχει σχήματα.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Εισαγόμενη διαφάνεια.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Καταργεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί.

--------------------

1) Για να αποφύγετε την εξίωση του PptxEditException, ελέγξτε πρώτα την ιδιότητα HasDependingSlides της διάταξης. 2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) για να απλοποιήσετε τον κώδικα.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Μετακινεί τη διαφάνεια διάταξης από τη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Στόχο δείκτη. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς μετακίνηση. |