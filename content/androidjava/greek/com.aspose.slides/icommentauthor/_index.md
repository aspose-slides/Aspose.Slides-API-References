---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an author of comments.
type: docs
url: /el/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Αναπαριστά έναν συντάκτη σχολίων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα του συντάκτη. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα του συντάκτη. |
| [getInitials()](#getInitials--) | Επιστρέφει ή ορίζει τα αρχικά του συντάκτη. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Επιστρέφει ή ορίζει τα αρχικά του συντάκτη. |
| [getComments()](#getComments--) | Επιστρέφει τη συλλογή των σχολίων που έκανε αυτός ο συντάκτης. |
| [remove()](#remove--) | Αφαιρεί τον συντάκτη από τη γονική συλλογή. |
### getName() {#getName--}
```
public abstract String getName()
```


Επιστρέφει ή ορίζει το όνομα του συντάκτη. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Επιστρέφει ή ορίζει το όνομα του συντάκτη. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Επιστρέφει ή ορίζει τα αρχικά του συντάκτη. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Επιστρέφει ή ορίζει τα αρχικά του συντάκτη. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Επιστρέφει τη συλλογή των σχολίων που έκανε αυτός ο συντάκτης. Μόνο για ανάγνωση [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Επιστρέφει:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Αφαιρεί τον συντάκτη από τη γονική συλλογή.