---
title: MasterSlideCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά μια συλλογή κύριων διαφανειών.
type: docs
url: /el/com.aspose.slides/masterslidecollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Αναπαριστά μια συλλογή κύριων διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στο συγκεκριμένο δείκτη. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο συγκεκριμένο δείκτη της συλλογής. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει έναν ριζικό αντικείμενο συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν αλγόριθμο που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Επιστρέφει το στοιχείο στο συγκεκριμένο δείκτη. Μόνο για ανάγνωση [MasterSlide](../../com.aspose.slides/masterslide).

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
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Η κύρια διαφάνεια προς αφαίρεση από τη συλλογή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στο συγκεκριμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί.

--------------------

Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides του master πριν.

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ignorePreserveField | boolean | Καθορίζει εάν αυτή η μέθοδος πρέπει να αφαιρέσει την αχρησιμοποίητη κύρια διαφάνεια ακόμα και αν η ιδιότητα [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) του έχει οριστεί σε true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στο τέλος της συλλογής. Οι συνδεδεμένες διαφάνειες διάταξης θα αντιγραφούν επίσης.

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

Εισάγει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. Οι συνδεδεμένες διαφάνειες διάταξης θα αντιγραφούν επίσης.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Δημιουργία αντικειμένου Presentation για φόρτωση του αρχικού αρχείου παρουσίασης
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Δημιουργία αντικειμένου Presentation για την προορισματική παρουσίαση (όπου θα κλωνοποιηθεί η διαφάνεια)
>      Presentation destPres = new Presentation();
>      try {
>          // Δημιουργία αντικειμένου ISlide από τη συλλογή διαφανειών στην αρχική παρουσίαση μαζί με
>          // Κύρια διαφάνεια
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Ανάκτηση των κύριων διαφανειών της προορισματικής παρουσίασης
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Κλωνοποίηση της επιθυμητής κύριας διαφάνειας από την αρχική παρουσίαση στη συλλογή των κύρων στη
>          // Προορισματική παρουσίαση
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Συλλογή διαφανειών στην προορισματική παρουσίαση
>          ISlideCollection slds = destPres.getSlides();
>          // Κλωνοποίηση της αρχικής διαφάνειας στη συλλογή διαφανειών της προορισματικής παρουσίασης.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Αποθήκευση της προορισματικής παρουσίασης στο δίσκο
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
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Διαφάνεια προς κλωνοποίηση. |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Εισαγμένη κύρια διαφάνεια.
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

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει έναν ριζικό αντικείμενο συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Επιστρέφει έναν αλγόριθμο που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.