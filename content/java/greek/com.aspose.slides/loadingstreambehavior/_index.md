---
title: LoadingStreamBehavior
second_title: Αναφορά API Aspose.Slides για Java
description: Το java.io.InputStream που περνάει σε μια μέθοδο θεωρείται ως Binary Large Object (BLOB) δείτε την περιγραφή.
type: docs
url: /el/com.aspose.slides/loadingstreambehavior/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Το java.io.InputStream που περνάει σε μια μέθοδο θεωρείται ως Binary Large Object (BLOB) (δείτε την περιγραφή του [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Οι τιμές αυτού του enum καθορίζουν πώς πρέπει να αντιμετωπίζεται το java.io.InputStream όταν περνά στη μέθοδο. Ανάλογα με τις απαιτήσεις, μπορούν να ληφθούν διαφορετικές αποφάσεις για να προσφέρουν τη πιο αποδοτική συμπεριφορά.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Η ροή θα διαβαστεί μέχρι το τέλος και στη συνέχεια θα απελευθερωθεί - δηλαδή |
| [KeepLocked](#KeepLocked) | Η ροή θα κλειδωθεί μέσα στο αντικείμενο [IPresentation](../../com.aspose.slides/ipresentation), δηλαδή |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Η ροή θα διαβαστεί μέχρι το τέλος και στη συνέχεια θα απελευθερωθεί - δηλαδή θα εγγυηθεί ότι αυτή η ροή δεν θα χρησιμοποιηθεί από το αντικείμενο [IPresentation](../../com.aspose.slides/ipresentation) στο μέλλον. Μπορεί να κλείσει από τον κώδικα του πελάτη ή να χρησιμοποιηθεί με οποιονδήποτε άλλο τρόπο.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // η ροή μπορεί να κλειστεί, δεν χρειάζεται πλέον για το "pres" αντικείμενο.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Η ροή θα κλειδωθεί μέσα στο αντικείμενο [IPresentation](../../com.aspose.slides/ipresentation), δηλαδή η ιδιοκτησία της ροής θα μεταβιβαστεί. Το αντικείμενο [IPresentation](../../com.aspose.slides/ipresentation) θα είναι υπεύθυνο για τη σωστή απελευθέρωση της ροής όταν αυτό το αντικείμενο απελευθερωθεί. Αυτή η συμπεριφορά είναι εξαιρετικά χρήσιμη όταν χρειάζεται να σειριοποιήσετε ένα μεγάλο αρχείο BLOB (όπως ένα μεγάλο βίντεο ή ήχο - δείτε την περιγραφή του [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) και θέλετε να αποτρέψετε τη φόρτωση αυτού του αρχείου στη μνήμη ή άλλα προβλήματα απόδοσης. Μπορείτε απλώς να ανοίξετε το java.io.FileInputStream για αυτό το αρχείο και να το περάσετε σε μια μέθοδο, επιλέγοντας το LoadingStreamBehavior του [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Δεν πρέπει να κλείσετε τη ροή ή να αλληλεπιδράσετε με αυτή με οποιονδήποτε άλλο τρόπο, θα οδηγήσει σε σφάλμα στη μέθοδο Save.
>    // Η fileStream θα χρησιμοποιηθεί για αποθήκευση, κάτι που θα αποτρέψει την υψηλή κατανάλωση μνήμης
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```