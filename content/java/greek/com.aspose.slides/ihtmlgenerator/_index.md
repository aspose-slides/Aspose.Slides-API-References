---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generator.
type: docs
url: /el/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Γεννήτρια HTML.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html)](#addHtml-char---) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addText(String text)](#addText-java.lang.String-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text)](#addText-char---) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Ενσωματώνει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Ενσωματώνει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Ενσωματώνει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html. |
| [getSlideImageSize()](#getSlideImageSize--) | Επιστρέφει το μέγεθος της εικόνας της διαφάνειας. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Επιστρέφει τη μονάδα στην οποία ορίζεται το μέγεθος της εικόνας της διαφάνειας. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Επιστρέφει έναν κώδικα CSS της μονάδας στην οποία ορίζεται το μέγεθος της εικόνας της διαφάνειας. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Επιστρέφει τον δείκτη της προηγούμενης απεικονισμένης διαφάνειας ή -1 αν είναι η πρώτη διαφάνεια σε απόδοση. |
| [getSlideIndex()](#getSlideIndex--) | Επιστρέφει τον δείκτη της τρέχουσας απεικονιζόμενης διαφάνειας. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Επιστρέφει τον δείκτη μιας διαφάνειας που θα απεικονισθεί μετά την τρέχουσα ή -1 αν είναι η τελευταία διαφάνεια. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```


Προσθέτει μορφοποιημένο κείμενο HTML.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| html | java.lang.String | Κείμενο προς προσθήκη. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```


Προσθέτει μορφοποιημένο κείμενο HTML.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| html | char[] | Κείμενο προς προσθήκη. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```


Προσθέτει μορφοποιημένο κείμενο HTML.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| html | char[] | Κείμενο προς προσθήκη. |
| startIndex | int | Δείκτης έναρξης του τμήματος προς προσθήκη. |
| length | int | Μήκος του τμήματος προς προσθήκη. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```


Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Δεν αντικαθίστανται αλλαγές γραμμής και κενά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς προσθήκη. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```


Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Δεν αντικαθίστανται αλλαγές γραμμής και κενά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | char[] | Κείμενο προς προσθήκη. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```


Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Δεν αντικαθίστανται αλλαγές γραμμής και κενά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | char[] | Κείμενο προς προσθήκη. |
| startIndex | int | Δείκτης έναρξης του τμήματος προς προσθήκη. |
| length | int | Μήκος του τμήματος προς προσθήκη. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```


Ενσωματώνει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```


Ενσωματώνει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```


Ενσωματώνει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |
| startIndex | int | Δείκτης έναρξης του τμήματος προς προσθήκη. |
| length | int | Μήκος του τμήματος προς προσθήκη. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```


Επιστρέφει το μέγεθος της εικόνας της διαφάνειας. Μόνο για ανάγνωση java.awt.geom.Dimension2D.

**Επιστρέφει:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```


Επιστρέφει τη μονάδα στην οποία ορίζεται το μέγεθος της εικόνας της διαφάνειας. Μόνο για ανάγνωση [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Επιστρέφει:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```


Επιστρέφει έναν κώδικα CSS της μονάδας στην οποία ορίζεται το μέγεθος της εικόνας της διαφάνειας. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```


Επιστρέφει τον δείκτη της προηγούμενης απεικονισμένης διαφάνειας ή -1 αν είναι η πρώτη διαφάνεια σε απόδοση. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```


Επιστρέφει τον δείκτη της τρέχουσας απεικονιζόμενης διαφάνειας. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```


Επιστρέφει τον δείκτη μιας διαφάνειας που θα απεικονισθεί μετά την τρέχουσα ή -1 αν είναι η τελευταία διαφάνεια. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int