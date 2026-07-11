---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης στην παρουσίαση.
type: docs
url: /el/com.aspose.slides/igloballayoutslidecollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης στην παρουσίαση. Επεκτείνει τη διεπαφή ILayoutSlideCollection με μεθόδους για την προσθήκη/κλωνοποίηση διαφανειών διάταξης στο πλαίσιο ενοποίησης των μεμονωμένων συλλογών των διαφανειών διάταξης του master.

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

Κατά την κλωνοποίηση μιας διάταξης μεταξύ διαφορετικών παρουσιάσεων, ο master της διάταξης μπορεί επίσης να κλωνοποιηθεί για να διατηρηθεί η μορφοποίηση της πηγής. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση αυτόματης κλωνοποίησης των master, ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master slide. Η χειροκίνητη κλωνοποίηση των master slides δεν θα αποτραπεί ούτε θα καταγραφεί.

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
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master διαφάνεια για μια νέα διάταξη. |

--------------------

Η νέα διάταξη θα συνδεθεί με τον ορισμένο master στην παρουσίαση προορισμού. Έτσι είναι το ανάλογο της λειτουργίας αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint.

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
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master διαφάνεια για μια νέα διάταξη. |
| layoutType | byte | Τύπος διάταξης για μια νέα διάταξη. Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για μια νέα διάταξη. Εάν το όνομα που παρασχέθηκε είναι ήδη σε χρήση, θα εξαχθεί ArgumentException. Εάν δοθεί παράμετρος null, τότε το όνομα θα παραχθεί αυτόματα με βάση τον δοσμένο τύπο διάταξης (για παράδειγμα "Title Slide" ή "1_Title Slide", "2_…", κλπ.). |

--------------------

1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει σύμβολα κράτησης θέσης και δεν έχει σχήματα. 2) Το ανάλογο αυτής της μεθόδου είναι η μέθοδος [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) η οποία προέρχεται από την ιδιότητα ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.