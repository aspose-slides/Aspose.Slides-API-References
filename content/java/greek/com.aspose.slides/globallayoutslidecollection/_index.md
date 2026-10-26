---
title: GlobalLayoutSlideCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης στην παρουσίαση.
type: docs
url: /el/com.aspose.slides/globallayoutslidecollection/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης στην παρουσίαση. Επεκτείνει την κλάση LayoutSlideCollection με μεθόδους για προσθήκη/κλωνοποίηση διαφανειών διάταξης στο πλαίσιο ενοποίησης των ατομικών συλλογών των κύριων διαφανειών διάταξης.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

Κατά την κλωνοποίηση μιας διάταξης μεταξύ διαφορετικών παρουσιάσεων, ο κύριος της διάταξης μπορεί επίσης να κλωνοποιηθεί ώστε να διατηρηθεί η μορφοποίηση της πηγής. Χρησιμοποιείται ένα εσωτερικό μητρώο για την παρακολούθηση αυτόματα κλωνοποιημένων κύριων διαφανειών ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων της ίδιας κύριας διαφάνειας. Η χειροκίνητη κλωνοποίηση των κύρων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Κύρια διαφάνεια για μια νέα διάταξη. |

--------------------

1) Η νέα διάταξη θα συνδεθεί με τον καθορισμένο κύριο στην παρουσίαση προορισμού. Έτσι είναι το αντίστοιχο του copy/paste με την επιλογή "Use Destination Theme" στο PowerPoint. 2) Το αντίστοιχο αυτής της μεθόδου είναι η μέθοδος [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) που προσπελάζεται με την ιδιότητα ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Κύρια διαφάνεια για μια νέα διάταξη. |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Εάν το παρεχόμενο όνομα χρησιμοποιείται ήδη, θα προκληθεί ArgumentException. Εάν δοθεί παράμετρος null, τότε το όνομα θα δημιουργηθεί αυτόματα με βάση τον παρεχόμενο τύπο διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_..", κλπ.). |

--------------------

1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει placeholders και σχήματα. 2) Το αντίστοιχο αυτής της μεθόδου είναι η μέθοδος [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) που προσπελάζεται με την ιδιότητα ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.