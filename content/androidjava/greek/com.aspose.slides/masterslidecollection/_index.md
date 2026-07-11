---
title: MasterSlideCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή κύριων διαφανειών.
type: docs
url: /el/com.aspose.slides/masterslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Αντιπροσωπεύει μια συλλογή κύριων διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στη συγκεκριμένη θέση. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Εισάγει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμομετρητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Επιστρέφει το στοιχείο στη συγκεκριμένη θέση. Μόνο για ανάγνωση [MasterSlide](../../com.aspose.slides/masterslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Η κύρια διαφάνεια που θα αφαιρεθεί από τη συλλογή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Η θέση (μηδενική βάση) του στοιχείου που θα αφαιρεθεί.

--------------------

Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides του κύριου πριν. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ignorePreserveField | boolean | Καθορίζει εάν αυτή η μέθοδος πρέπει να αφαιρέσει αχρησιμοποίητους κύριους ακόμη και αν η ιδιότητα [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) του οριστεί σε true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Προσθέτει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στο τέλος της συλλογής. Οι συνδεδεμένες διαφάνειες διάταξης θα αντιγραφούν επίσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Διαφάνεια προς κλωνοποίηση. |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Προστέθηκε διαφάνεια.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Εισάγει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. Οι συνδεδεμένες διαφάνειες διάταξης θα αντιγραφούν επίσης.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Δημιουργία αντικειμένου Presentation για φόρτωση του αρχείου πηγαίας παρουσίασης
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Δημιουργία αντικειμένου Presentation για προορισματική παρουσίαση (where slide is to be cloned)
>      Presentation destPres = new Presentation();
>      try {
>          // Δημιουργία ISlide από τη συλλογή διαφανειών στην πηγαία παρουσίαση μαζί με
>          // Master slide
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Get Master Slides of destination presentation
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clone the desired master slide from the source presentation to the collection of masters in the
>          // Destination presentation
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Collection of slides in the destination presentation
>          ISlideCollection slds = destPres.getSlides();
>          // Clone source slide to destination slides collection.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Save the destination presentation to disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
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
| index | int | Θέση της νέας διαφάνειας. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Διαφάνεια προς κλωνοποίηση. |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Εισαχθείσα κύρια διαφάνεια.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας-στόχος. |
| index | int | Αρχική θέση στον πίνακα-στόχο. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Επιστρέφει έναν αριθμομετρητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διαδρομή της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.