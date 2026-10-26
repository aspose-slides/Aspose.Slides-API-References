---
title: HtmlGenerator
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
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

| Method | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html)](#addHtml-char---) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addText(String text)](#addText-java.lang.String-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text)](#addText-char---) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Περιβάλλει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Περιβάλλει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Περιβάλλει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html. |
| [getSlideImageSize()](#getSlideImageSize--) | Επιστρέφει το μέγεθος της εικόνας της διαφάνειας. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Επιστρέφει τη μονάδα με την οποία καθορίζεται το μέγεθος της εικόνας της διαφάνειας. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Επιστρέφει έναν κωδικό css της μονάδας στην οποία καθορίζεται το μέγεθος της εικόνας της διαφάνειας. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Επιστρέφει το δείκτη της προηγούμενης εμφανιζόμενης διαφάνειας ή -1 εάν η πρώτη διαφάνεια βρίσκεται σε απόδοση. |
| [getSlideIndex()](#getSlideIndex--) | Επιστρέφει το δείκτη της τρέχουσας διαφάνειας σε απόδοση. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Επιστρέφει το δείκτη μιας διαφάνειας που θα εμφανιστεί μετά την τρέχουσα ή -1 εάν η τρέχουσα είναι η τελευταία διαφάνεια. |

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

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Οι αλλαγές γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς προσθήκη. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Οι αλλαγές γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | char[] | Κείμενο προς προσθήκη. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Οι αλλαγές γραμμής και τα κενά δεν αντικαθίστανται.

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

Περιβάλλει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Περιβάλλει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Περιβάλλει την τιμή του χαρακτηριστικού σε εισαγωγικά και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |
| startIndex | int | Αρχικός δείκτης του τμήματος προς προσθήκη. |
| length | int | Μήκος του τμήματος προς προσθήκη. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

Επιστρέφει το μέγεθος της εικόνας της διαφάνειας. Μόνο για ανάγνωση [SizeF](../../com.aspose.slides.android/sizef).

**Επιστρέφει:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Επιστρέφει τη μονάδα με την οποία καθορίζεται το μέγεθος της εικόνας της διαφάνειας. Μόνο για ανάγνωση [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Επιστρέφει:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Επιστρέφει έναν κωδικό css της μονάδας στην οποία καθορίζεται το μέγεθος της εικόνας της διαφάνειας. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Επιστρέφει το δείκτη της προηγούμενης εμφανιζόμενης διαφάνειας ή -1 εάν η πρώτη διαφάνεια βρίσκεται σε απόδοση. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Επιστρέφει το δείκτη της τρέχουσας διαφάνειας σε απόδοση. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Επιστρέφει το δείκτη μιας διαφάνειας που θα εμφανιστεί μετά την τρέχουσα ή -1 εάν η τρέχουσα είναι η τελευταία διαφάνεια. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int