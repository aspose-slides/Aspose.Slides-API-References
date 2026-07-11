---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Παρέχει επιλογές που ελέγχουν την εμφάνιση της διάταξης των σημειώσεων και των σχολίων στο εξαχθέν έγγραφο.
type: docs
url: /el/com.aspose.slides/notescommentslayoutingoptions/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση της διάταξης των σημειώσεων και των σχολίων στο εξαχθέν έγγραφο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Προεπιλεγμένος κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Λαμβάνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Λαμβάνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. |
| [getNotesPosition()](#getNotesPosition--) | Λαμβάνει ή ορίζει τη θέση των σημειώσεων στη σελίδα. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Λαμβάνει ή ορίζει τη θέση των σημειώσεων στη σελίδα. |
| [getCommentsPosition()](#getCommentsPosition--) | Λαμβάνει ή ορίζει τη θέση των σχολίων στη σελίδα. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Λαμβάνει ή ορίζει τη θέση των σχολίων στη σελίδα. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Λαμβάνει ή ορίζει το χρώμα της περιοχής σχολίων (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Λαμβάνει ή ορίζει το χρώμα της περιοχής σχολίων (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Λαμβάνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε pixels (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Λαμβάνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε pixels (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Προεπιλεγμένος κατασκευαστής.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Λαμβάνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. Εάν είναι true, τότε τα σχόλια θα εμφανίζονται. (Εφαρμόζεται μόνο εάν εμφανίζονται τα σχόλια).

--------------------

Η προεπιλεγμένη τιμή είναι **false**.

**Επιστρέφει:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Λαμβάνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. Εάν είναι true, τότε τα σχόλια θα εμφανίζονται. (Εφαρμόζεται μόνο εάν εμφανίζονται τα σχόλια).

--------------------

Η προεπιλεγμένη τιμή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Λαμβάνει ή ορίζει τη θέση των σημειώσεων στη σελίδα.

--------------------

Η προεπιλογή είναι **NotesPositions.None**.

**Επιστρέφει:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Λαμβάνει ή ορίζει τη θέση των σημειώσεων στη σελίδα.

--------------------

Η προεπιλογή είναι **NotesPositions.None**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Λαμβάνει ή ορίζει τη θέση των σχολίων στη σελίδα.

--------------------

Η προεπιλογή είναι **CommentsPositions.None**.

**Επιστρέφει:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Λαμβάνει ή ορίζει τη θέση των σχολίων στη σελίδα.

--------------------

Η προεπιλογή είναι **CommentsPositions.None**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


Λαμβάνει ή ορίζει το χρώμα της περιοχής σχολίων (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά).

--------------------

Η προεπιλογή είναι **SkyBlue**.

**Επιστρέφει:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


Λαμβάνει ή ορίζει το χρώμα της περιοχής σχολίων (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά).

--------------------

Η προεπιλογή είναι **SkyBlue**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Λαμβάνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε pixels (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά).

--------------------

Η ελάχιστη και προεπιλεγμένη τιμή είναι **150**.

**Επιστρέφει:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Λαμβάνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε pixels (Εφαρμόζεται μόνο εάν τα σχόλια εμφανίζονται δεξιά).

--------------------

Η ελάχιστη και προεπιλεγμένη τιμή είναι **150**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |