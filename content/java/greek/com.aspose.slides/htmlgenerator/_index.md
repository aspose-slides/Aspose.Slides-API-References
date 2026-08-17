---
title: HtmlGenerator
second_title: Aspose.Slides για την Αναφορά API της Java
description: Δημιουργός HTML.
type: docs
url: /el/com.aspose.slides/htmlgenerator/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Δημιουργός HTML.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html)](#addHtml-char---) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addText(String text)](#addText-java.lang.String-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text)](#addText-char---) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Τοποθετεί σε εισαγωγικά την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Τοποθετεί σε εισαγωγικά την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Τοποθετεί σε εισαγωγικά την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html. |
| [getSlideImageSize()](#getSlideImageSize--) | Επιστρέφει το μέγεθος της εικόνας της διαφάνειας. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Επιστρέφει τη μονάδα μέτρησης στην οποία ορίζεται το μέγεθος της εικόνας διαφάνειας. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Επιστρέφει έναν κώδικα CSS της μονάδας στην οποία ορίζεται το μέγεθος της εικόνας διαφάνειας. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Επιστρέφει τον δείκτη της προηγουμένως αποδομημένης διαφάνειας ή -1 αν η πρώτη διαφάνεια βρίσκεται σε απόδοση. |
| [getSlideIndex()](#getSlideIndex--) | Επιστρέφει τον δείκτη της τρέχουσας διαφάνειας σε απόδοση. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Επιστρέφει τον δείκτη μιας διαφάνειας που θα αποδοθεί μετά την τρέχουσα διαφάνεια ή -1 αν αποδίδεται η τελευταία διαφάνεια. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Προσθέτει μορφοποιημένο κείμενο HTML.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| html | java.lang.String | Κείμενο προς προσθήκη. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Προσθέτει μορφοποιημένο κείμενο HTML.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| html | char[] | Κείμενο προς προσθήκη. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Προσθέτει μορφοποιημένο κείμενο HTML.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| html | char[] | Κείμενο προς προσθήκη. |
| startIndex | int | Αρχικός δείκτης του τμήματος προς προσθήκη. |
| length | int | Μήκος του τμήματος προς προσθήκη. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Τα διαλείμματα γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς προσθήκη. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Τα διαλείμματα γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | char[] | Κείμενο προς προσθήκη. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Τα διαλείμματα γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | char[] | Κείμενο προς προσθήκη. |
| startIndex | int | Αρχικός δείκτης του τμήματος προς προσθήκη. |
| length | int | Μήκος του τμήματος προς προσθήκη. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Τοποθετεί σε εισαγωγικά την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Τοποθετεί σε εισαγωγικά την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Τοποθετεί σε εισαγωγικά την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |
| startIndex | int | Αρχικός δείκτης του τμήματος προς προσθήκη. |
| length | int | Μήκος του τμήματος προς προσθήκη. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Επιστρέφει το μέγεθος της εικόνας της διαφάνειας. Μόνο-ανάγνωση java.awt.geom.Dimension2D.

**Επιστρέφει:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Επιστρέφει τη μονάδα μέτρησης στην οποία ορίζεται το μέγεθος της εικόνας διαφάνειας. Μόνο-ανάγνωση [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Επιστρέφει:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Επιστρέφει έναν κώδικα CSS της μονάδας στην οποία ορίζεται το μέγεθος της εικόνας διαφάνειας. Μόνο-ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Επιστρέφει τον δείκτη της προηγουμένως αποδομημένης διαφάνειας ή -1 αν η πρώτη διαφάνεια βρίσκεται σε απόδοση. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Επιστρέφει τον δείκτη της τρέχουσας διαφάνειας σε απόδοση. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Επιστρέφει τον δείκτη μιας διαφάνειας που θα αποδοθεί μετά την τρέχουσα διαφάνεια ή -1 αν αποδίδεται η τελευταία διαφάνεια. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int