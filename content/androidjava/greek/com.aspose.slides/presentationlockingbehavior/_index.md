---
title: PresentationLockingBehavior
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη μεταχείριση του αρχείου πηγής ή του java.io.InputStream κατά τη φόρτωση και εργασία με ένα στιγμιότυπο του.
type: docs
url: /el/com.aspose.slides/presentationlockingbehavior/
---
**Κληρονομικότητα:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη μεταχείριση της πηγής [IPresentation](../../com.aspose.slides/ipresentation) (αρχείου ή java.io.InputStream) κατά τη φόρτωση και εργασία με ένα στιγμιότυπο του [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Η πηγή είναι η παράμετρος που περνιέται στον κατασκευαστή [IPresentation](../../com.aspose.slides/ipresentation). Στο παρακάτω παράδειγμα, η πηγή είναι το αρχείο "pres.pptx": Για αυτό το παράδειγμα, η πηγή ("pres.pptx" αρχείο) θα είναι κλειδωμένη για τη διάρκεια ζωής μιας περίπτωσης [IPresentation](../../com.aspose.slides/ipresentation), δηλαδή δεν μπορεί να αλλάξει ή να διαγραφεί από άλλη διαδικασία.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Η πηγή θα είναι κλειδωμένη μόνο για τη διάρκεια της εκτέλεσης του κατασκευαστή [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | Η πηγή θα είναι κλειδωμένη για ολόκληρη τη διάρκεια ζωής της παρουσίασης [IPresentation](../../com.aspose.slides/ipresentation), μέχρι να διαγραφεί. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

Η πηγή θα είναι κλειδωμένη μόνο για τη διάρκεια της εκτέλεσης του κατασκευαστή [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Εάν ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) οριστεί σε false, όλα τα BLOB θα φορτωθούν στη μνήμη. Διαφορετικά, μπορεί να χρησιμοποιηθούν άλλοι τρόποι, όπως προσωρινά αρχεία.

--------------------

Αυτή η συμπεριφορά είναι πιο αργή από το [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), και εάν είναι δυνατόν να μεταβιβαστεί η ιδιοκτησία της πηγής στο [IPresentation](../../com.aspose.slides/ipresentation), συνιστάται η χρήση του [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Η πηγή θα είναι κλειδωμένη για ολόκληρη τη διάρκεια ζωής της παρουσίασης [IPresentation](../../com.aspose.slides/ipresentation), μέχρι να διαγραφεί.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) πρέπει να οριστεί σε true για τη χρήση αυτής της συμπεριφοράς, διαφορετικά θα ριχτεί εξαίρεση.

--------------------

Αυτή η συμπεριφορά συνιστάται, είναι ταχύτερη και καταναλώνει λιγότερη μνήμη από το [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).