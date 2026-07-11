---
title: Section
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τμήμα διαφανειών.
type: docs
url: /el/com.aspose.slides/section/
---
**Κληρονομιά:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Αντιπροσωπεύει τμήμα διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Όνομα του τμήματος. |
| [setName(String value)](#setName-java.lang.String-) | Όνομα του τμήματος. |
| [getSectionId()](#getSectionId--) | Αναγνωριστικό Τμήματος. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Επιστρέφει την πρώτη διαφάνεια του τμήματος. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Επιστρέφει λίστα διαφανειών στο τμήμα. |
### getName() {#getName--}
```
public final String getName()
```


Όνομα του τμήματος.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Όνομα του τμήματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Αναγνωριστικό Τμήματος.

**Επιστρέφει:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Επιστρέφει την πρώτη διαφάνεια του τμήματος.

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Επιστρέφει λίστα διαφανειών στο τμήμα.

**Επιστρέφει:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Λίστα διαφανειών.