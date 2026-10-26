---
title: SectionCollection
second_title: Aspose.Slides για την αναφορά API Java
description: Αντιπροσωπεύει μια συλλογή ενοτήτων.
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

Αντιπροσωπεύει μια συλλογή ενοτήτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο ευρετήριο. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Προσθέτει ενότητα διαφανειών που ξεκινά από συγκεκριμένη διαφάνεια. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Προσθέτει κενή ενότητα στο τέλος της συλλογής. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Προσθέτει κενή ενότητα στη συγκεκριμένη θέση της συλλογής. |
| [size()](#size--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πράγματι στη συλλογή. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Επιστρέφει έναν δείκτη της καθορισμένης ενότητας στη συλλογή. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Αφαιρεί την ενότητα και τις διαφάνειες που περιέχονται στην ενότητα. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Αφαιρεί την ενότητα. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Μετακινεί την ενότητα και τις διαφάνειες της από τη συλλογή στην καθορισμένη θέση. |
| [clear()](#clear--) | Αφαιρεί όλες τις ενότητες από τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διαπερνά τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Λαμβάνει το στοιχείο στο καθορισμένο ευρετήριο. Μόνο προς ανάγνωση [ISection](../../com.aspose.slides/isection).

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

Προσθέτει ενότητα διαφανειών που ξεκινά από συγκεκριμένη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Πρώτη διαφάνεια της ενότητας |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Ενότητα που προστέθηκε.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Προσθέτει κενή ενότητα στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Ενότητα που προστέθηκε.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Προσθέτει κενή ενότητα στην καθορισμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |
| index | int | Δείκτης της νέας ενότητας. |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Ενότητα που προστέθηκε.
### size() {#size--}
```
public final int size()
```

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πράγματι στη συλλογή. Μόνο προς ανάγνωση int.

**Επιστρέφει:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Επιστρέφει έναν δείκτη της καθορισμένης ενότητας στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα προς εύρεση. |

**Επιστρέφει:**
int - Δείκτης ενότητας ή -1 εάν η ενότητα δεν ανήκει σε αυτή τη συλλογή.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Αφαιρεί την ενότητα και τις διαφάνειες που περιέχονται στην ενότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Η ενότητα που θα αφαιρεθεί από τη συλλογή. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Αφαιρεί την ενότητα. Οι διαφάνειες που περιέχονται στην ενότητα θα συγχωνευτούν με την προηγούμενη ενότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Η ενότητα που θα αφαιρεθεί από τη συλλογή. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Μετακινεί την ενότητα και τις διαφάνειες της από τη συλλογή στην καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα προς μετακίνηση. |
| index | int | Δείκτης προορισμού. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλες τις ενότητες από τη συλλογή.

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

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο προς ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο προς ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Επιστρέφει έναν απαριθμητή που διαπερνά τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.