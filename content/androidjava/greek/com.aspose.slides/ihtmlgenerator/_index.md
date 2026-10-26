---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Γεννήτρια Html.
type: docs
url: /el/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Γεννήτρια Html.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html)](#addHtml-char---) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Προσθέτει μορφοποιημένο κείμενο HTML. |
| [addText(String text)](#addText-java.lang.String-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text)](#addText-char---) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Παραθέτει την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Παραθέτει την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Παραθέτει την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html. |
| [getSlideImageSize()](#getSlideImageSize--) | Επιστρέφει το μέγεθος εικόνας της διαφάνειας. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Επιστρέφει τη μονάδα στην οποία καθορίζεται το μέγεθος εικόνας της διαφάνειας. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Επιστρέφει έναν κώδικα CSS της μονάδας στην οποία καθορίζεται το μέγεθος εικόνας της διαφάνειας. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Επιστρέφει το ευρετήριο της προηγούμενης διαφάνειας που έχει αποδοθεί ή -1 αν αποδίδεται η πρώτη διαφάνεια. |
| [getSlideIndex()](#getSlideIndex--) | Επιστρέφει το ευρετήριο της τρέχουσας διαφάνειας που αποδίδεται. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Επιστρέφει το ευρετήριο μιας διαφάνειας που θα αποδοθεί μετά την τρέχουσα ή -1 αν αποδίδεται η τελευταία διαφάνεια. |

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
| startIndex | int | Δείκτης έναρξης του τμήματος που θα προστεθεί. |
| length | int | Μήκος του τμήματος που θα προστεθεί. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Τα διαλείμματα γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς προσθήκη. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Τα διαλείμματα γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | char[] | Κείμενο προς προσθήκη. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Προσθέτει απλό κείμενο στα αρχεία html, αντικαθιστώντας ειδικούς χαρακτήρες με οντότητες html. Τα διαλείμματα γραμμής και τα κενά δεν αντικαθίστανται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | char[] | Κείμενο προς προσθήκη. |
| startIndex | int | Δείκτης έναρξης του τμήματος που θα προστεθεί. |
| length | int | Μήκος του τμήματος που θα προστεθεί. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Παραθέτει την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Παραθέτει την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Παραθέτει την τιμή του χαρακτηριστικού και την προσθέτει στο αρχείο html.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char[] | Συμβολοσειρά τιμής χαρακτηριστικού. |
| startIndex | int | Δείκτης έναρξης του τμήματος που θα προστεθεί. |
| length | int | Μήκος του τμήματος που θα προστεθεί. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Επιστρέφει το μέγεθος εικόνας της διαφάνειας. Μόνο για ανάγνωση [SizeF](../../com.aspose.slides.android/sizef).

**Τιμή επιστροφής:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Επιστρέφει τη μονάδα στην οποία καθορίζεται το μέγεθος εικόνας της διαφάνειας. Μόνο για ανάγνωση [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Τιμή επιστροφής:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Επιστρέφει έναν κώδικα CSS της μονάδας στην οποία καθορίζεται το μέγεθος εικόνας της διαφάνειας. Μόνο για ανάγνωση String.

**Τιμή επιστροφής:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Επιστρέφει το ευρετήριο της προηγούμενης διαφάνειας που έχει αποδοθεί ή -1 αν αποδίδεται η πρώτη διαφάνεια. Μόνο για ανάγνωση int.

**Τιμή επιστροφής:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Επιστρέφει το ευρετήριο της τρέχουσας διαφάνειας που αποδίδεται. Μόνο για ανάγνωση int.

**Τιμή επιστροφής:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Επιστρέφει το ευρετήριο μιας διαφάνειας που θα αποδοθεί μετά την τρέχουσα ή -1 αν αποδίδεται η τελευταία διαφάνεια. Μόνο για ανάγνωση int.

**Τιμή επιστροφής:**
int