---
title: SectionCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/sectioncollection/
---
## SectionCollection κλάση

 Represents a collection of sections.
 
### addEmptySection {#addEmptySection}

| Όνομα | Περιγραφή |
| --- | --- |
| addEmptySection (String, int) | Add empty section to specified position of the collection. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Name of the section |
| index | int | Index of new section. |

 **Επιστρέφει:**
[Section](../section)


---


### addSection {#addSection}

| Όνομα | Περιγραφή |
| --- | --- |
| addSection (String, [Slide](../slide)) | Add slides section started form specific slide. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Name of the section |
| startedFromSlide | [Slide](../slide) | First slide of section |

 **Επιστρέφει:**
[Section](../section)


---


### appendEmptySection {#appendEmptySection}

| Όνομα | Περιγραφή |
| --- | --- |
| appendEmptySection (String) | Add empty section to the end of the collection. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Name of the section |

 **Επιστρέφει:**
[Section](../section)


---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Removes all sections from the collection. |

 **Επιστρέφει:**
void


---


### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Επιστρέφει:**
Object


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. Read-only ISection. |

 **Επιστρέφει:**
[Section](../section)


---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([Section](../section)) | Returns an index of the specified section in the collection. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [Section](../section) | Section to find. |

 **Επιστρέφει:**
int


---


### isSynchronized {#isSynchronized}

| Όνομα | Περιγραφή |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Επιστρέφει:**



---


### iteratorJava {#iteratorJava}

| Όνομα | Περιγραφή |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Επιστρέφει:**



---


### removeSection {#removeSection}

| Όνομα | Περιγραφή |
| --- | --- |
| removeSection ([Section](../section)) | Remove section. Slides contained in the section will be merged into previous section. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [Section](../section) | The section to remove from the collection. |

 **Επιστρέφει:**
void


---


### removeSectionWithSlides {#removeSectionWithSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| removeSectionWithSlides ([Section](../section)) | Remove section and slides contained in the section. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [Section](../section) | The section to remove from the collection. |

 **Επιστρέφει:**
void


---


### reorderSectionWithSlides {#reorderSectionWithSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| reorderSectionWithSlides ([Section](../section), int) | Moves section and its slides from the collection to the specified position. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | [Section](../section) | Target index. |
| section | int | Section to move. |

 **Επιστρέφει:**
void


---


### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Επιστρέφει:**
int


---