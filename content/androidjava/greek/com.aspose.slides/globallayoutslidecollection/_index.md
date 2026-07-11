---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή από όλες τις διαφάνειες διάταξης στην παρουσίαση.
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

Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης στην παρουσίαση. Επεκτείνει την κλάση LayoutSlideCollection με μεθόδους για προσθήκη/κλωνοποίηση διαφανειών διάταξης στο πλαίσιο ενοποίησης των ατομικών συλλογών των διαφανειών διάταξης του κύριου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην παρουσίαση. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην παρουσίαση. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Προσθέτει μια νέα διαφάνεια διάταξης στην παρουσίαση. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

--------------------

Όταν κλωνοποιείται μια διάταξη μεταξύ διαφορετικών παρουσιάσεων, ο κύριος της διάταξης μπορεί επίσης να κλωνοποιηθεί για να διατηρηθεί η διαμόρφωση της πηγής. Χρησιμοποιείται εσωτερικό μητρώο για την αυτόματη παρακολούθηση των κλωνοποιημένων κυρίων, ώστε να αποτρέπεται η δημιουργία πολλαπλών κλώνων της ίδιας κύριας διαφάνειας. Η χειροκίνητη κλωνοποίηση κυρίων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί.

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Κύρια διαφάνεια για μια νέα διάταξη. |

--------------------

1) Η νέα διάταξη θα συνδεθεί με τον ορισμένο κύριο στην προοριστική παρουσίαση. Έτσι λειτουργεί ως αντίστοιχο της εντολής αντιγραφή/επικόλληση με την επιλογή «Χρήση Θέματος Προορισμού» στο PowerPoint. 2) Το αντίστοιχο αυτής της μεθόδου είναι η μέθοδος [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) προσπελάσιμη μέσω της ιδιότητας ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

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
| layoutType | byte | Υποστηριζόμενοι τύποι διάταξης: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Άλλοι τύποι διάταξης δεν υποστηρίζονται αυτή τη στιγμή: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Όνομα για τη νέα διάταξη. Αν το δοθέν όνομα είναι ήδη σε χρήση, θα προκληθεί ArgumentException. Αν περάσει τιμή null, το όνομα θα δημιουργηθεί αυτόματα σύμφωνα με τον τύπο διάταξης (για παράδειγμα «Title Slide» ή «1_Title Slide», «2_…», κλπ.). |

--------------------

1) Η προστιθέμενη διάταξη για την τιμή SlideLayoutType.Custom του layoutType δεν περιέχει δεσμευτικά σημεία ή σχήματα. 2) Το αντίστοιχο αυτής της μεθόδου είναι η μέθοδος [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) προσπελάσιμη μέσω της ιδιότητας ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Προστέθηκε διαφάνεια.