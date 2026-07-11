---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /el/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Διεπαφή callback που χρησιμοποιείται για τον καθορισμό του τρόπου επεξεργασίας του αντικειμένου κατά την αποθήκευση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Επιστρέφει ένα URL σε εξωτερικό αντικείμενο. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Αποθηκεύει εξωτερικό αντικείμενο. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο. Αυτή η μέθοδος καλείται μία φορά για κάθε αναγνωριστικό αντικειμένου. Δεν υπάρχει εγγύηση ότι δεν θα υπάρχουν δύο αντικείμενα με τα ίδια δεδομένα, semanticName και contentType αλλά διαφορετικό id.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int | Αναγνωριστικό αντικειμένου. Αυτό το αναγνωριστικό είναι μοναδικό για ολόκληρη τη λειτουργία αποθήκευσης. |
| entityData | byte[] | Δυαδικά δεδομένα αντικειμένου. Αυτή η παράμετρος μπορεί να είναι null, εάν τα δυαδικά δεδομένα του αντικειμένου δεν έχουν δημιουργηθεί ακόμη. |
| semanticName | java.lang.String | Κάποιο σύντομο κείμενο που περιγράφει το νόημα του αντικειμένου. Ο ελεγκτής μπορεί να το χρησιμοποιήσει ως μέρος του ονόματος του εξωτερικού αντικειμένου, αλλά εξαρτάται από τον διαχειριστή να εξασφαλίσει ότι τα ονόματα θα είναι μοναδικά και θα περιέχουν μόνο επιτρεπόμενους χαρακτήρες. |
| contentType | java.lang.String | Τύπος MIME του αντικειμένου. |
| recomendedExtension | java.lang.String | Επέκταση ονόματος αρχείου, προτεινόμενη για αυτό το τύπο MIME. |

**Επιστρέφει:**
int - Απόφαση
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Επιστρέφει ένα URL σε εξωτερικό αντικείμενο. Αυτή η μέθοδος καλείται πάντα εάν η \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) επέστρεψε [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) και μπορεί να κληθεί εάν η \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) επέστρεψε [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) αλλά η ενσωμάτωση είναι αδύνατη. Μπορεί να κληθεί πολλαπλές φορές για το ίδιο αναγνωριστικό αντικειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int | Αναγνωριστικό αντικειμένου. Αυτό το αναγνωριστικό είναι μοναδικό για ολόκληρη τη λειτουργία αποθήκευσης. |
| referrer | int | Αναγνωριστικό αντικειμένου-αναφορέα ή 0, εάν το αντικείμενο αναφέρεται από το ριζικό έγγραφο. Μπορεί να χρησιμοποιηθεί για τη δημιουργία σχετικού συνδέσμου. |

**Επιστρέφει:**
java.lang.String - Url του εξωτερικού αντικειμένου ή null εάν αυτό το αντικείμενο πρέπει να αγνοηθεί.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Αποθηκεύει εξωτερικό αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int | Αναγνωριστικό αντικειμένου. Αυτό το αναγνωριστικό είναι μοναδικό για ολόκληρη τη λειτουργία αποθήκευσης. |
| entityData | byte[] | Δυαδικά δεδομένα αντικειμένου. Αυτή η παράμετρος δεν μπορεί να είναι null. |