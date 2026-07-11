---
title: BlobManagementOptions
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση κανόνων χειρισμού BLOB και άλλων ρυθμίσεων BLOB.
type: docs
url: /el/com.aspose.slides/blobmanagementoptions/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Αναπαριστά επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση κανόνων διαχείρισης BLOB και άλλων ρυθμίσεων BLOB.
## Κατασκευαστές

| Constructor | Περιγραφή |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Δημιουργεί νέες προεπιλεγμένες επιλογές διαχείρισης blob. |
## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Αυτή η ιδιότητα ορίζει αν ένα στιγμιότυπο της κλάσης Presentation μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής - κατά τη διάρκεια ζωής του στιγμιότυπου. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Αυτή η ιδιότητα ορίζει αν ένα στιγμιότυπο της κλάσης Presentation μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής - κατά τη διάρκεια ζωής του στιγμιότυπου. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Αυτή η ιδιότητα ορίζει αν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOB, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης, αλλά απαιτεί δικαιώματα δημιουργίας αρχείων. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Αυτή η ιδιότητα ορίζει αν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOB, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης, αλλά απαιτεί δικαιώματα δημιουργίας αρχείων. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Η ρίζα διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Η ρίζα διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που όλα τα BLOB μπορεί να καταλαμβάνουν στη μνήμη. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που όλα τα BLOB μπορεί να καταλαμβάνουν στη μνήμη. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Δημιουργεί νέες προεπιλεγμένες επιλογές διαχείρισης blob.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Αυτή η ιδιότητα ορίζει αν ένα στιγμιότυπο της κλάσης Presentation μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής - κατά τη διάρκεια ζωής του στιγμιότυπου. Εάν το στιγμιότυπο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOB, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια ζωής του στιγμιότυπου Presentation.

**Επιστρέφει:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Αυτή η ιδιότητα ορίζει αν ένα στιγμιότυπο της κλάσης Presentation μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής - κατά τη διάρκεια ζωής του στιγμιότυπου. Εάν το στιγμιότυπο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOB, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια ζωής του στιγμιότυπου Presentation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Αυτή η ιδιότητα ορίζει αν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOB, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης, αλλά απαιτεί δικαιώματα δημιουργίας αρχείων.

--------------------

Όλα τα αρχεία θα διαγραφούν μετά το τέλος της εργασίας με την παρουσίαση.

**Επιστρέφει:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Αυτή η ιδιότητα ορίζει αν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOB, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης, αλλά απαιτεί δικαιώματα δημιουργίας αρχείων.

--------------------

Όλα τα αρχεία θα διαγραφούν μετά το τέλος της εργασίας με την παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Η ρίζα διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Ο προεπιλεγμένος κατάλογος προσωρινών αρχείων του συστήματος θα χρησιμοποιηθεί. Η διαδικασία φιλοξενίας πρέπει να έχει δικαιώματα δημιουργίας αρχείων και φακέλων εκεί.

**Επιστρέφει:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Η ρίζα διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Ο προεπιλεγμένος κατάλογος προσωρινών αρχείων του συστήματος θα χρησιμοποιηθεί. Η διαδικασία φιλοξενίας πρέπει να έχει δικαιώματα δημιουργίας αρχείων και φακέλων εκεί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που όλα τα BLOB μπορεί να καταλαμβάνουν στη μνήμη. Προεπιλογή είναι όλα τα BLOB να φορτώνονται στη μνήμη· μόλις φτάσει αυτό το όριο, χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOB στη μνήμη βελτιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτή την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας.

--------------------

Αυτή η ιδιότητα αγνοείται εάν \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) είναι ορισμένη σε false, διότι η μνήμη είναι τότε η μόνη διαθέσιμη τοποθεσία αποθήκευσης και ο περιορισμός της χρήσης BLOB στη μνήμη δεν έχει αποτέλεσμα.

--------------------

Η προεπιλεγμένη τιμή είναι 629 145 600 bytes (600 MB).

--------------------

Μπορείτε να ορίσετε αυτή την ιδιότητα σε μηδέν, αλλά ένα μικρό ελάχιστο ποσό μνήμης θα παραμείνει δεσμευμένο.

**Επιστρέφει:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που όλα τα BLOB μπορεί να καταλαμβάνουν στη μνήμη. Προεπιλογή είναι όλα τα BLOB να φορτώνονται στη μνήμη· μόλις φτάσει αυτό το όριο, χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOB στη μνήμη βελτιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτή την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας.

--------------------

Αυτή η ιδιότητα αγνοείται εάν \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) είναι ορισμένη σε false, διότι η μνήμη είναι τότε η μόνη διαθέσιμη τοποθεσία αποθήκευσης και ο περιορισμός της χρήσης BLOB στη μνήμη δεν έχει αποτέλεσμα.

--------------------

Η προεπιλεγμένη τιμή είναι 629 145 600 bytes (600 MB).

--------------------

Μπορείτε να ορίσετε αυτή την ιδιότητα σε μηδέν, αλλά ένα μικρό ελάχιστο ποσό μνήμης θα παραμείνει δεσμευμένο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |