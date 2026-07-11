---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
url: /el/com.aspose.slides/isection/
---```
public interface ISection
```

Αντιπροσωπεύει την ενότητα των διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Όνομα της ενότητας. |
| [setName(String value)](#setName-java.lang.String-) | Όνομα της ενότητας. |
| [getSectionId()](#getSectionId--) | Αναγνωριστικό Ενότητας. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Επιστρέφει την πρώτη διαφάνεια της ενότητας. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Επιστρέφει τη λίστα διαφανειών στην ενότητα. |
### getName() {#getName--}
```
public abstract String getName()
```


Όνομα της ενότητας.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Όνομα της ενότητας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


Αναγνωριστικό Ενότητας.

**Επιστρέφει:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Επιστρέφει την πρώτη διαφάνεια της ενότητας.

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Επιστρέφει τη λίστα διαφανειών στην ενότητα.

**Επιστρέφει:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Λίστα διαφανειών [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)