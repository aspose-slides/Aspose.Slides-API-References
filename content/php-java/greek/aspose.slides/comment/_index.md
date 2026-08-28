---
title: Comment
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/comment/
---
## Κλάση Comment

Αντιπροσωπεύει ένα σχόλιο σε μια διαφάνεια.

### getAuthor {#getAuthor}

| Όνομα | Περιγραφή |
| --- | --- |
| getAuthor () | Επιστρέφει τον συγγραφέα ενός σχολίου. Μόνο για ανάγνωση ICommentAuthor. |

**Επιστρέφει:**
[CommentAuthor](../commentauthor)

---

### getCreatedTime {#getCreatedTime}

| Όνομα | Περιγραφή |
| --- | --- |
| getCreatedTime () | Επιστρέφει ή ορίζει το χρόνο δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε java.util.Date(Long.MIN_VALUE) σημαίνει ότι δεν έχει οριστεί χρόνος σχολίου. Ανάγνωση/εγγραφή java.util.Date. Ο χρόνος σχολίου είναι προαιρετική παράμετρος. |

**Επιστρέφει:**
Date

---

### getParentComment {#getParentComment}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentComment () | Λαμβάνει ή ορίζει το γονικό σχόλιο. Ανάγνωση/εγγραφή IComment. |

**Επιστρέφει:**
[Comment](../comment), [ModernComment](../moderncomment)

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| PptxEditException | Εκκινείται όταν η ρύθμιση της τιμής οδηγεί σε κυκλική αναφορά |

---

### getPosition {#getPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| getPosition () | Επιστρέφει ή ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float. |

**Επιστρέφει:**
Point2D.Float

---

### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει ή ορίζει την γονική διαφάνεια ενός σχολίου. Μόνο για ανάγνωση ISlide. |

**Επιστρέφει:**
[Slide](../slide)

---

### getText {#getText}

| Όνομα | Περιγραφή |
| --- | --- |
| getText () | Επιστρέφει ή ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String

---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove () | Καταργεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| PptxEditException | Εκκινείται εάν το σχόλιο έχει ήδη καταργηθεί |

---

### setCreatedTime {#setCreatedTime}

| Όνομα | Περιγραφή |
| --- | --- |
| setCreatedTime (Date) | Επιστρέφει ή ορίζει το χρόνο δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε java.util.Date(Long.MIN_VALUE) σημαίνει ότι δεν έχει οριστεί χρόνος σχολίου. Ανάγνωση/εγγραφή java.util.Date. Ο χρόνος σχολίου είναι προαιρετική παράμετρος. |

**Επιστρέφει:**
void

---

### setParentComment {#setParentComment}

| Όνομα | Περιγραφή |
| --- | --- |
| setParentComment ([Comment](../comment)) | Λαμβάνει ή ορίζει το γονικό σχόλιο. Ανάγνωση/εγγραφή IComment. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| PptxEditException | Εκκινείται όταν η ρύθμιση της τιμής οδηγεί σε κυκλική αναφορά |

---

### setParentComment {#setParentComment}

| Όνομα | Περιγραφή |
| --- | --- |
| setParentComment ([ModernComment](../moderncomment)) | Λαμβάνει ή ορίζει το γονικό σχόλιο. Ανάγνωση/εγγραφή IComment. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| PptxEditException | Εκκινείται όταν η ρύθμιση της τιμής οδηγεί σε κυκλική αναφορά |

---

### setPosition {#setPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| setPosition (Point2D.Float) | Επιστρέφει ή ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float. |

**Επιστρέφει:**
void

---

### setText {#setText}

| Όνομα | Περιγραφή |
| --- | --- |
| setText (String) | Επιστρέφει ή ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void

---