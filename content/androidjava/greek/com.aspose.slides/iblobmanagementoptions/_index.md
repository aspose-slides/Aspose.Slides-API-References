---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Ένα Binary Large Object (BLOB) είναι ένα δυαδικό δεδομένο που αποθηκεύεται ως μια ενιαία οντότητα - π.χ.
type: docs
url: /el/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Ένα Binary Large Object (BLOB) είναι ένα δυαδικό δεδομένο που αποθηκεύεται ως μια ενιαία οντότητα - π.χ. το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. Χρησιμοποιούνται διάφορες τεχνικές για τη βελτιστοποίηση της κατανάλωσης μνήμης κατά την εργασία με BLOBs – είτε το BLOB είναι ήδη αποθηκευμένο στην παρουσίαση είτε προστίθεται αργότερα προγραμματιστικά. Χρησιμοποιώντας [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) μπορείτε να αλλάξετε διαφορετικές πτυχές της συμπεριφοράς σχετικά με τη διαχείριση BLOBs για τη διάρκεια ζωής του αντικειμένου [IPresentation](../../com.aspose.slides/ipresentation).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Αυτή η ιδιότητα ορίζει εάν ένα αντικείμενο της κλάσης Presentation μπορεί να είναι κάτοχος του πηγαίου αρχείου ή ρεύματος κατά τη διάρκεια της ζωής του αντικειμένου. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Αυτή η ιδιότητα ορίζει εάν ένα αντικείμενο της κλάσης Presentation μπορεί να είναι κάτοχος του πηγαίου αρχείου ή ρεύματος κατά τη διάρκεια της ζωής του αντικειμένου. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Αυτή η ιδιότητα ορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, γεγονός που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί άδειες για δημιουργία αρχείων. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Αυτή η ιδιότητα ορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, γεγονός που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί άδειες για δημιουργία αρχείων. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Αυτή η ιδιότητα ορίζει εάν ένα αντικείμενο της κλάσης Presentation μπορεί να είναι κάτοχος του πηγαίου αρχείου ή ρεύματος κατά τη διάρκεια της ζωής του αντικειμένου. Εάν το αντικείμενο είναι κάτοχος, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOBs, αλλά η πηγή (ρεύμα ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια της ζωής του αντικειμένου Presentation. Αυτό είναι ένα παράδειγμα:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Θα εξαχθεί IOException επειδή το pres.pptx είναι κλειδωμένο για τη διάρκεια ζωής του Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Μετά την απελευθέρωση του αντικειμένου Presentation, το αρχείο ξεκλειδώνεται και μπορεί να διαγραφεί
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Επιστρέφει:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Αυτή η ιδιότητα ορίζει εάν ένα αντικείμενο της κλάσης Presentation μπορεί να είναι κάτοχος του πηγαίου αρχείου ή ρεύματος κατά τη διάρκεια της ζωής του αντικειμένου. Εάν το αντικείμενο είναι κάτοχος, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOBs, αλλά η πηγή (ρεύμα ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια της ζωής του αντικειμένου Presentation. Αυτό είναι ένα παράδειγμα:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Θα εξαχθεί IOException επειδή το pres.pptx είναι κλειδωμένο για τη διάρκεια ζωής του Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // μετά την απελευθέρωση του αντικειμένου Presentation, το αρχείο ξεκλειδώνεται και μπορεί να διαγραφεί
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Αυτή η ιδιότητα ορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, γεγονός που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί άδειες για δημιουργία αρχείων.

--------------------

Όλα τα αρχεία θα διαγραφούν μετά το τέλος της εργασίας με την παρουσίαση.

**Επιστρέφει:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Αυτή η ιδιότητα ορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, γεγονός που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί άδειες για δημιουργία αρχείων.

--------------------

Όλα τα αρχεία θα διαγραφούν μετά το τέλος της εργασίας με την παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Προεπιλογή είναι ο σύστημα προσωρινών καταλόγων. Η διεργασία φιλοξενίας πρέπει να έχει άδειες για δημιουργία αρχείων και φακέλων εκεί.

**Επιστρέφει:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Προεπιλογή είναι ο σύστημα προσωρινών καταλόγων. Η διεργασία φιλοξενίας πρέπει να έχει άδειες για δημιουργία αρχείων και φακέλων εκεί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Από προεπιλογή, όλα τα BLOBs φορτώνονται στη μνήμη· μόνο όταν φτάσει αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτήν την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας.

--------------------

Αυτή η ιδιότητα παραλείπεται εάν \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) είναι ορισμένη σε false, καθώς η μνήμη είναι τότε ο μοναδικός διαθέσιμος χώρος αποθήκευσης και ο περιορισμός της χρήσης BLOBs στη μνήμη δεν έχει αποτέλεσμα.

--------------------

Η προεπιλεγμένη τιμή είναι 629 145 600 bytes (600 MB).

--------------------

Μπορείτε να ορίσετε αυτήν την ιδιότητα σε μηδέν, αλλά θα διατηρηθεί ένα μικρό ελάχιστο ποσό μνήμης.

**Επιστρέφει:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Από προεπιλογή, όλα τα BLOBs φορτώνονται στη μνήμη· μόνο όταν φτάσει αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτήν την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας.

--------------------

Αυτή η ιδιότητα παραλείπεται εάν \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) είναι ορισμένη σε false, καθώς η μνήμη είναι τότε ο μοναδικός διαθέσιμος χώρος αποθήκευσης και ο περιορισμός της χρήσης BLOBs στη μνήμη δεν έχει αποτέλεσμα.

--------------------

Η προεπιλεγμένη τιμή είναι 629 145 600 bytes (600 MB).

--------------------

Μπορείτε να ορίσετε αυτήν την ιδιότητα σε μηδέν, αλλά θα διατηρηθεί ένα μικρό ελάχιστο ποσό μνήμης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |