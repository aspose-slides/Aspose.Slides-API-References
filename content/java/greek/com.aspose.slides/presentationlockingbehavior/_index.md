---
title: PresentationLockingBehavior
second_title: Aspose.Slides για την αναφορά API της Java
description: Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη διαχείριση του  αρχείου πηγής ή του  java.io.InputStream κατά τη φόρτωση και εργασία με ένα στιγμιότυπο του .
type: docs
url: /el/com.aspose.slides/presentationlockingbehavior/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη διαχείριση της [IPresentation](../../com.aspose.slides/ipresentation) πηγής (αρχείο ή java.io.InputStream) κατά τη φόρτωση και εργασία με ένα στιγμιότυπο του [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Η πηγή είναι η παράμετρος που περνάται στον κατασκευαστή [IPresentation](../../com.aspose.slides/ipresentation). Στο παρακάτω παράδειγμα, η πηγή είναι το αρχείο "pres.pptx": Για αυτό το παράδειγμα, η πηγή ("pres.pptx" file) θα κλειδωθεί για ένα [IPresentation](../../com.aspose.slides/ipresentation) στιγμιότυπο, δηλαδή δεν μπορεί να αλλάξει ή να διαγραφεί από άλλη διαδικασία.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Η πηγή θα κλειδωθεί μόνο για το χρόνο εκτέλεσης του κατασκευαστή [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | Η πηγή θα κλειδωθεί για ολόκληρη τη διάρκεια ενός στιγμιότυπου [IPresentation](../../com.aspose.slides/ipresentation), μέχρι να απελευθερωθεί. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


Η πηγή θα κλειδωθεί μόνο για το χρόνο εκτέλεσης του κατασκευαστή [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Αν ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) οριστεί σε false, όλα τα BLOB θα φορτωθούν στη μνήμη. Διαφορετικά, μπορεί να χρησιμοποιηθούν άλλα μέσα, όπως προσωρινά αρχεία.

--------------------

Αυτή η συμπεριφορά είναι πιο αργή από το [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), και εάν είναι δυνατόν να μεταβιβαστεί η ιδιοκτησία της πηγής στο [IPresentation](../../com.aspose.slides/ipresentation), συνιστάται η χρήση του [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


Η πηγή θα κλειδωθεί για ολόκληρη τη διάρκεια ενός στιγμιότυπου [IPresentation](../../com.aspose.slides/ipresentation), μέχρι να απελευθερωθεί.

--------------------

Το [IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) πρέπει να οριστεί σε true για τη χρήση αυτής της συμπεριφοράς, διαφορετικά θα εξαπολυθεί εξαίρεση.

--------------------

Αυτή η συμπεριφορά συνιστάται, είναι ταχύτερη και καταναλώνει λιγότερη μνήμη από το [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).