---
title: NotesCommentsLayoutingOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν την εμφάνιση της διάταξης των σημειώσεων και σχολίων στο εξαγόμενο έγγραφο.
type: docs
url: /el/com.aspose.slides/notescommentslayoutingoptions/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση της διάταξης των σημειώσεων και σχολίων στο εξαγόμενο έγγραφο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Προεπιλεγμένος κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Παίρνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Παίρνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. |
| [getNotesPosition()](#getNotesPosition--) | Παίρνει ή ορίζει τη θέση των σημειώσεων στη σελίδα. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Παίρνει ή ορίζει τη θέση των σημειώσεων στη σελίδα. |
| [getCommentsPosition()](#getCommentsPosition--) | Παίρνει ή ορίζει τη θέση των σχολίων στη σελίδα. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Παίρνει ή ορίζει τη θέση των σχολίων στη σελίδα. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Παίρνει ή ορίζει το χρώμα της περιοχής σχολίων (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | Παίρνει ή ορίζει το χρώμα της περιοχής σχολίων (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Παίρνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε εικονοστοιχεία (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Παίρνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε εικονοστοιχεία (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Κατασκευαστής προεπιλογής.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Παίρνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. Εάν true, τότε τα σχόλια θα εμφανιστούν. (Ισχύει μόνο αν τα σχόλια εμφανίζονται).

--------------------

Η προεπιλεγμένη τιμή είναι **false**.

**Επιστρέφει:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Παίρνει ή ορίζει την ορατότητα των σχολίων που δεν έχουν συγγραφέα. Εάν true, τότε τα σχόλια θα εμφανιστούν. (Ισχύει μόνο αν τα σχόλια εμφανίζονται).

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

Παίρνει ή ορίζει τη θέση των σημειώσεων στη σελίδα.

--------------------

Η προεπιλεγμένη τιμή είναι **NotesPositions.None**.

**Επιστρέφει:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Παίρνει ή ορίζει τη θέση των σημειώσεων στη σελίδα.

--------------------

Η προεπιλεγμένη τιμή είναι **NotesPositions.None**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Παίρνει ή ορίζει τη θέση των σχολίων στη σελίδα.

--------------------

Η προεπιλεγμένη τιμή είναι **CommentsPositions.None**.

**Επιστρέφει:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Παίρνει ή ορίζει τη θέση των σχολίων στη σελίδα.

--------------------

Η προεπιλεγμένη τιμή είναι **CommentsPositions.None**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

Παίρνει ή ορίζει το χρώμα της περιοχής σχολίων (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά).

--------------------

Η προεπιλεγμένη τιμή είναι **Color.SkyBlue**.

**Επιστρέφει:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

Παίρνει ή ορίζει το χρώμα της περιοχής σχολίων (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά).

--------------------

Η προεπιλεγμένη τιμή είναι **Color.SkyBlue**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Color |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Παίρνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε εικονοστοιχεία (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά).

--------------------

Η ελάχιστη και προεπιλεγμένη τιμή είναι **150**.

**Επιστρέφει:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Παίρνει ή ορίζει το πλάτος της περιοχής εξόδου σχολίων σε εικονοστοιχεία (Ισχύει μόνο αν τα σχόλια εμφανίζονται στα δεξιά).

--------------------

Η ελάχιστη και προεπιλεγμένη τιμή είναι **150**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |