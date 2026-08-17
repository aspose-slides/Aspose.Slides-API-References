---
title: ISectionCollection
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει μια συλλογή από ενότητες.
type: docs
url: /el/com.aspose.slides/isectioncollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Αντιπροσωπεύει μια συλλογή από ενότητες.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στην καθορισμένη θέση. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Προσθέτει νέα ενότητα που ξεκινά από συγκεκριμένη διαφάνεια. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Προσθέτει κενή ενότητα στη καθορισμένη θέση της συλλογής. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Αφαιρεί την ενότητα και τις διαφάνειες που περιέχει. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Αφαιρεί την ενότητα. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Μετακινεί την ενότητα και τις διαφάνειες της από τη συλλογή στην καθορισμένη θέση. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Προσθέτει κενή ενότητα στο τέλος της συλλογής. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Επιστρέφει το δείκτη της καθορισμένης ενότητας στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλες τις ενότητες από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Επιστρέφει το στοιχείο στην καθορισμένη θέση. Μόνο για ανάγνωση [ISection](../../com.aspose.slides/isection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Προσθέτει νέα ενότητα που ξεκινά από συγκεκριμένη διαφάνεια.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Πρώτη διαφάνεια της ενότητας |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστιθέμενη ενότητα.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Προσθέτει κενή ενότητα στη καθορισμένη θέση της συλλογής.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |
| index | int | Δείκτης της νέας ενότητας. |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστιθέμενη ενότητα.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Αφαιρεί την ενότητα και τις διαφάνειες που περιέχει.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Η ενότητα που θα αφαιρεθεί από τη συλλογή. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Αφαιρεί την ενότητα. Οι διαφάνειες που περιέχονται στην ενότητα θα συγχωνευτούν με την προηγούμενη ενότητα.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Η ενότητα που θα αφαιρεθεί από τη συλλογή. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Μετακινεί την ενότητα και τις διαφάνειες της από τη συλλογή στην καθορισμένη θέση.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα προς μετακίνηση. |
| index | int | Στόχος δείκτη. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Προσθέτει κενή ενότητα στο τέλος της συλλογής.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ενότητας |

**Επιστρέφει:**
[ISection](../../com.aspose.slides/isection) - Προστιθέμενη ενότητα.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Επιστρέφει το δείκτη της καθορισμένης ενότητας στη συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα προς εύρεση. |

**Επιστρέφει:**
int - Δείκτης μιας ενότητας ή -1 αν η ενότητα δεν ανήκει σε αυτή τη συλλογή.
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις ενότητες από τη συλλογή.