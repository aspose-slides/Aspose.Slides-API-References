---
title: LoadingStreamBehavior
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs

url: /el/aspose.slides/loadingstreambehavior/
---
## Κλάση LoadingStreamBehavior

 Το java.io.InputStream που περνάει σε μια μέθοδο θεωρείται ως Binary Large Object (BLOB) (δείτε την περιγραφή του IBlobManagementOptions). Οι τιμές αυτής της απαρίθμησης προσδιορίζουν πώς πρέπει να αντιμετωπιστεί το java.io.InputStream όταν περνάει στη μέθοδο. Ανάλογα με τις απαιτήσεις, μπορούν να ληφθούν διαφορετικές αποφάσεις για να παρασχεθεί η πιο αποδοτική συμπεριφορά. 

## Σταθερές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
[ReadStreamAndRelease](#ReadStreamAndRelease) | 0 | Η ροή θα διαβαστεί μέχρι το τέλος και στη συνέχεια θα απελευθερωθεί - δηλαδή θα εξασφαλιστεί ότι αυτή η ροή δεν θα χρησιμοποιείται από το στιγμιότυπο IPresentation στο μέλλον. Μπορεί να κλείσει από τον κώδικα του πελάτη ή να χρησιμοποιηθεί με οποιονδήποτε άλλο τρόπο. Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // η ροή μπορεί να κλείσει, δεν χρειάζεται πλέον για το "pres" object. } finally { if (pres != null) pres.dispose(); } |
[KeepLocked](#KeepLocked) | 1 | Η ροή θα κλειδωθεί μέσα στο αντικείμενο IPresentation, δηλαδή η ιδιοκτησία της ροής θα μεταβιβαστεί. Το αντικείμενο IPPresentation θα είναι υπεύθυνο να απελευθερώσει σωστά τη ροή όταν αυτό το αντικείμενο απελευθερωθεί. Αυτή η συμπεριφορά είναι εξαιρετικά χρήσιμη όταν χρειάζεται να σειριοποιήσετε ένα μεγάλο αρχείο BLOB (όπως ένα μεγάλο βίντεο ή ήχο - δείτε την περιγραφή του IBlobManagementOptions) και θέλετε να αποτρέψετε τη φόρτωση αυτού του αρχείου στη μνήμη ή άλλα προβλήματα απόδοσης. Μπορείτε απλώς να ανοίξετε το java.io.FileInputStream για αυτό το αρχείο και να το περάσετε σε μια μέθοδο, επιλέγοντας LoadingStreamBehavior#KeepLocked LoadingStreamBehavior. Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // Δεν πρέπει να κλείσετε τη ροή ή να αλληλεπιδράσετε με αυτή με οποιονδήποτε άλλο τρόπο, θα οδηγήσει σε σφάλμα στη μέθοδο Save. // Το fileStream θα χρησιμοποιηθεί για αποθήκευση, κάτι που θα αποτρέψει τη μεγάλη κατανάλωση μνήμης pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); } |

---

### ReadStreamAndRelease {#ReadStreamAndRelease}
Η ροή θα διαβαστεί μέχρι το τέλος και στη συνέχεια θα απελευθερωθεί - δηλαδή θα εξασφαλιστεί ότι αυτή η ροή δεν θα χρησιμοποιείται από το στιγμιότυπο IPresentation στο μέλλον. Μπορεί να κλείσει από τον κώδικα του πελάτη ή να χρησιμοποιηθεί με οποιονδήποτε άλλο τρόπο. Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // η ροή μπορεί να κλείσει, δεν χρειάζεται πλέον για το "pres" object. } finally { if (pres != null) pres.dispose(); }

---

### KeepLocked {#KeepLocked}
Η ροή θα κλειδωθεί μέσα στο αντικείμενο IPresentation, δηλαδή η ιδιοκτησία της ροής θα μεταβιβαστεί. Το αντικείμενο IPPresentation θα είναι υπεύθυνο να απελευθερώσει σωστά τη ροή όταν αυτό το αντικείμενο απελευθερωθεί. Αυτή η συμπεριφορά είναι εξαιρετικά χρήσιμη όταν χρειάζεται να σειριοποιήσετε ένα μεγάλο αρχείο BLOB (όπως ένα μεγάλο βίντεο ή ήχο - δείτε την περιγραφή του IBlobManagementOptions) και θέλετε να αποτρέψετε τη φόρτωση αυτού του αρχείου στη μνήμη ή άλλα προβλήματα απόδοσης. Μπορείτε απλώς να ανοίξετε το java.io.FileInputStream για αυτό το αρχείο και να το περάσετε σε μια μέθοδο, επιλέγοντας LoadingStreamBehavior#KeepLocked LoadingStreamBehavior. Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // Δεν πρέπει να κλείσετε τη ροή ή να αλληλεπιδράσετε με αυτή με οποιονδήποτε άλλο τρόπο, θα οδηγήσει σε σφάλμα στη μέθοδο Save. // Το fileStream θα χρησιμοποιηθεί για αποθήκευση, κάτι που θα αποτρέψει τη μεγάλη κατανάλωση μνήμης pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); }

---