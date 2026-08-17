---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: Represents an author of comments.
type: docs
url: /el/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Αναπαριστά έναν συγγραφέα σχολίων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα του συγγραφέα. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα του συγγραφέα. |
| [getInitials()](#getInitials--) | Επιστρέφει ή ορίζει τις αρχικογράμματα του συγγραφέα. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Επιστρέφει ή ορίζει τις αρχικογράμματα του συγγραφέα. |
| [getComments()](#getComments--) | Επιστρέφει τη συλλογή των σχολίων που έγιναν από αυτόν τον συγγραφέα. |
| [remove()](#remove--) | Αφαιρεί το συγγραφέα από τη γονική συλλογή. |
### getName() {#getName--}
```
public abstract String getName()
```


Επιστρέφει ή ορίζει το όνομα του συγγραφέα. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Επιστρέφει ή ορίζει το όνομα του συγγραφέα. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Επιστρέφει ή ορίζει τις αρχικογράμματα του συγγραφέα. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Επιστρέφει ή ορίζει τις αρχικογράμματα του συγγραφέα. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Επιστρέφει τη συλλογή των σχολίων που έγιναν από αυτόν τον συγγραφέα. Μόνο ανάγνωση [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Επιστρέφει:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Αφαιρεί το συγγραφέα από τη γονική συλλογή.