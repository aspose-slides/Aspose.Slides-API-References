---
title: IComment
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει ένα σχόλιο σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/icomment/
---```
public interface IComment
```

Αντιπροσωπεύει ένα σχόλιο σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getText()](#getText--) | Επιστρέφει ή ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. |
| [setText(String value)](#setText-java.lang.String-) | Επιστρέφει ή ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. |
| [getCreatedTime()](#getCreatedTime--) | Επιστρέφει ή ορίζει τον χρόνο δημιουργίας ενός σχολίου. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Επιστρέφει ή ορίζει τον χρόνο δημιουργίας ενός σχολίου. |
| [getSlide()](#getSlide--) | Επιστρέφει ή ορίζει τη γονική διαφάνεια ενός σχολίου. |
| [getAuthor()](#getAuthor--) | Επιστρέφει τον συγγγράφο ενός σχολίου. |
| [getPosition()](#getPosition--) | Επιστρέφει ή ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Επιστρέφει ή ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. |
| [remove()](#remove--) | Αφαιρεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή. |
| [getParentComment()](#getParentComment--) | Ανακτά ή ορίζει γονικό σχόλιο. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Ανακτά ή ορίζει γονικό σχόλιο. |
### getText() {#getText--}
```
public abstract String getText()
```

Επιστρέφει ή ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Επιστρέφει ή ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Επιστρέφει ή ορίζει τον χρόνο δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε java.util.Date(Long.MIN\_VALUE) σημαίνει ότι δεν έχει οριστεί χρόνος σχολίου. Ανάγνωση/εγγραφή java.util.Date.

--------------------

Ο χρόνος σχολίου είναι προαιρετική παράμετρος.

**Επιστρέφει:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Επιστρέφει ή ορίζει τον χρόνο δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε java.util.Date(Long.MIN\_VALUE) σημαίνει ότι δεν έχει οριστεί χρόνος σχολίου. Ανάγνωση/εγγραφή java.util.Date.

--------------------

Ο χρόνος σχολίου είναι προαιρετική παράμετρος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Επιστρέφει ή ορίζει τη γονική διαφάνεια ενός σχολίου. Μόνο-ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Επιστρέφει τον συγγγράφο ενός σχολίου. Μόνο-ανάγνωση [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Επιστρέφει ή ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. Ανάγνωση/εγγραφή android.graphics.PointF.

**Επιστρέφει:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Επιστρέφει ή ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. Ανάγνωση/εγγραφή android.graphics.PointF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

Αφαιρεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Ανακτά ή ορίζει γονικό σχόλιο. Ανάγνωση/εγγραφή [IComment](../../com.aspose.slides/icomment).

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Ανακτά ή ορίζει γονικό σχόλιο. Ανάγνωση/εγγραφή [IComment](../../com.aspose.slides/icomment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |