---
title: LoadingStreamBehavior
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Το java.io.InputStream που περνιέται σε μια μέθοδο θεωρείται ως Μεγάλο Δυαδικό Αντικείμενο (BLOB) δείτε την περιγραφή.
type: docs
url: /el/com.aspose.slides/loadingstreambehavior/
---
**Κληρονομικότητα:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Η java.io.InputStream που περνιέται σε μια μέθοδο θεωρείται ως Μεγάλο Δυαδικό Αντικείμενο (BLOB) (δείτε την περιγραφή [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Οι τιμές αυτής της απαρίθμησης προσδιορίζουν πώς πρέπει να αντιμετωπίζεται η java.io.InputStream όταν περνιέται στη μέθοδο. Ανάλογα με τις απαιτήσεις, μπορούν να ληφθούν διαφορετικές αποφάσεις για την παροχή της πιο αποδοτικής συμπεριφοράς.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Το ρεύμα θα διαβαστεί μέχρι το τέλος και στη συνέχεια θα απελευθερωθεί - δηλαδή |
| [KeepLocked](#KeepLocked) | Το ρεύμα θα κλειδωθεί μέσα στο αντικείμενο [IPresentation](../../com.aspose.slides/ipresentation), δηλαδή |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Το ρεύμα θα διαβαστεί μέχρι το τέλος και στη συνέχεια θα απελευθερωθεί - δηλαδή θα εγγυηθεί ότι αυτό το ρεύμα δεν θα χρησιμοποιηθεί από την παρουσία [IPresentation](../../com.aspose.slides/ipresentation) στο μέλλον. Μπορεί να κλείσει από τον κώδικα του πελάτη ή να χρησιμοποιηθεί με οποιονδήποτε άλλο τρόπο.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // το ρεύμα μπορεί να κλείσει, δεν χρειάζεται πλέον για το αντικείμενο "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Το ρεύμα θα κλειδωθεί μέσα στο αντικείμενο [IPresentation](../../com.aspose.slides/ipresentation), δηλαδή η ιδιοκτησία του ρεύματος θα μεταβιβαστεί. Το αντικείμενο [IPresentation](../../com.aspose.slides/ipresentation) θα είναι υπεύθυνο να απελευθύνει σωστά το ρεύμα όταν αυτό το αντικείμενο θα απελευθερωθεί από μόνο του. Αυτή η συμπεριφορά είναι εξαιρετικά χρήσιμη όταν χρειάζεται να σειριοποιήσετε ένα μεγάλο αρχείο BLOB (όπως ένα μεγάλο βίντεο ή ήχο - δείτε την περιγραφή [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) και θέλετε να αποτρέψετε τη φόρτωση του αρχείου στη μνήμη ή άλλα προβλήματα απόδοσης. Μπορείτε απλώς να ανοίξετε το java.io.FileInputStream για αυτό το αρχείο και να το περάσετε σε μια μέθοδο, επιλέγοντας [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Δεν πρέπει να κλείσετε το ρεύμα ή να αλληλεπιδράσετε με αυτό με οποιονδήποτε άλλο τρόπο, θα προκαλέσει σφάλμα στη μέθοδο Save.
>    // Το fileStream θα χρησιμοποιηθεί για αποθήκευση, κάτι που θα αποτρέψει υψηλή κατανάλωση μνήμης
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
