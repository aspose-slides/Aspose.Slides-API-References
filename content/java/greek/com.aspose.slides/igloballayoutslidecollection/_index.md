---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά μια συλλογή από όλες τις διαφάνειες διάταξης στην παρουσίαση.
type: docs
url: /el/com.aspose.slides/igloballayoutslidecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Αναπαριστά μια συλλογή όλων των διαφανειών διάταξης στην παρουσίαση. Επεκτείνει τη διεπαφή ILayoutSlideCollection με μεθόδους για προσθήκη/κλωνοποίηση διαφανειών διάταξης στο πλαίσιο της ενοποίησης των επιμέρους συλλογών των διαφανειών master.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

Όταν κλωνοποιείται μια διάταξη μεταξύ διαφορετικών παρουσιάσεων, μπορεί επίσης να κλωνοποιηθεί το master της διάταξης για να διατηρηθεί η μορφοποίηση της πηγής. Χρησιμοποιείται εσωτερικό μητρώο για την αυτόματη παρακολούθηση κλωνοποιημένων master, προκειμένου να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master slide. Η χειροκίνητη κλωνοποίηση master slide δεν θα εμποδιστεί ούτε θα καταγραφεί.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide για τη νέα διάταξη. |

--------------------

Η νέα διάταξη θα συνδεθεί με τον ορισμένο master στην προοριστική παρουσίαση. Έτσι λειτουργεί ως ανάλογο της λειτουργίας αντιγραφής/επικόλλησης με την επιλογή «Use Destination Theme» στο PowerPoint.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide για τη νέα διάταξη. |
| layoutType | byte | Τύπος διάταξης για τη νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτήν τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για τη νέα διάταξη. Εάν το δοσμένο όνομα είναι ήδη σε χρήση, θα ριφθεί ArgumentException. Εάν περαστεί null παράμετρος, το όνομα θα δημιουργηθεί αυτόματα σύμφωνα με τον δοσμένο τύπο διάταξης (π.χ. "Title Slide" ή "1_Title Slide", "2_..", κλπ). |

--------------------

1) Προστέθηκε διάταξη για την τιμή SlideLayoutType.Custom του layoutType που δεν περιέχει δείκτες θέσης και σχήματα. 2) Αναλογία αυτής της μεθόδου είναι η μέθοδος [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) που προσπερνάται με την ιδιότητα ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.