---
title: ISectionCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια συλλογή από ενότητες.
type: docs
url: /el/com.aspose.slides/isectioncollection/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Αντιπροσωπεύει μια συλλογή από ενότητες.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στον καθορισμένο δείκτη. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Προσθέτει νέα ενότητα που ξεκινά από συγκεκριμένη διαφάνεια. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Προσθέτει κενή ενότητα στη συγκεκριμένη θέση της συλλογής. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Αφαιρεί την ενότητα και τις διαφάνειες που περιέχει. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Αφαιρεί την ενότητα. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Μετακινεί την ενότητα και τις διαφάνειές της από τη συλλογή στη συγκεκριμένη θέση. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Προσθέτει κενή ενότητα στο τέλος της συλλογής. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Επιστρέφει έναν δείκτη της συγκεκριμένης ενότητας στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλες τις ενότητες από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Αποκτά το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [ISection](../../com.aspose.slides/isection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Προσθέτει νέα ενότητα που ξεκινά από συγκεκριμένη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Πρώτη διαφάνεια της ενότητας |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστέθηκε η ενότητα.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Προσθέτει κενή ενότητα στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |
| index | int | Δείκτης νέας ενότητας. |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστέθηκε η ενότητα.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Αφαιρεί την ενότητα και τις διαφάνειες που περιέχει.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Η ενότητα που θα αφαιρεθεί από τη συλλογή. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Αφαιρεί την ενότητα. Οι διαφάνειες που περιέχονται στην ενότητα θα συγχωνευτούν στην προηγούμενη ενότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Η ενότητα που θα αφαιρεθεί από τη συλλογή. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Μετακινεί την ενότητα και τις διαφάνειές της από τη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα προς μετακίνηση. |
| index | int | Δείκτης προορισμού. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Προσθέτει κενή ενότητα στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστέθηκε η ενότητα.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Επιστρέφει έναν δείκτη της συγκεκριμένης ενότητας στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα προς εύρεση. |

**Επιστρέφει:**
int - Δείκτης ενότητας ή -1 εάν η ενότητα δεν προέρχεται από αυτή τη συλλογή.
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις ενότητες από τη συλλογή.