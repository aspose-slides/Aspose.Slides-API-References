---
title: SectionCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή τμημάτων.
type: docs
url: /el/com.aspose.slides/sectioncollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Αναπαριστά μια συλλογή τμημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Προσθέτει τμήμα διαφανειών που ξεκινά από συγκεκριμένη διαφάνεια. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Προσθέτει κενό τμήμα στο τέλος της συλλογής. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Προσθέτει κενό τμήμα στην καθορισμένη θέση της συλλογής. |
| [size()](#size--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Επιστρέφει έναν δείκτη του καθορισμένου τμήματος στη συλλογή. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Αφαιρεί το τμήμα και τις διαφάνειες που περιέχονται στο τμήμα. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Αφαιρεί το τμήμα. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Μετακινεί το τμήμα και τις διαφάνειες του από τη συλλογή στη συγκεκριμένη θέση. |
| [clear()](#clear--) | Αφαιρεί όλα τα τμήματα από τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν αρίθμητο που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [ISection](../../com.aspose.slides/isection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```


Προσθέτει τμήμα διαφανειών που ξεκινά από συγκεκριμένη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του τμήματος |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Πρώτη διαφάνεια του τμήματος |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστέθηκε το τμήμα.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```


Προσθέτει κενό τμήμα στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του τμήματος |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστέθηκε το τμήμα.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```


Προσθέτει κενό τμήμα στην καθορισμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του τμήματος |
| index | int | Δείκτης του νέου τμήματος. |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστέθηκε το τμήμα.
### size() {#size--}
```
public final int size()
```


Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```


Επιστρέφει έναν δείκτη του καθορισμένου τμήματος στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα προς εύρεση. |

**Επιστρέφει:**
int - Δείκτης τμήματος ή -1 αν το τμήμα δεν ανήκει σε αυτή τη συλλογή.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```


Αφαιρεί το τμήμα και τις διαφάνειες που περιέχονται στο τμήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Το τμήμα που θα αφαιρεθεί από τη συλλογή. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```


Αφαιρεί το τμήμα. Οι διαφάνειες που περιέχονται στο τμήμα θα συγχωνευτούν με το προηγούμενο τμήμα.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Το τμήμα που θα αφαιρεθεί από τη συλλογή. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```


Μετακινεί το τμήμα και τις διαφάνειες του από τη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα προς μετακίνηση. |
| index | int | Στόχος δείκτη. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα τμήματα από τη συλλογή.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού |
| index | int | Δείκτης στον πίνακα προορισμού. |

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
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```


Επιστρέφει έναν αρίθμητο που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διασχίση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστέ

φει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.