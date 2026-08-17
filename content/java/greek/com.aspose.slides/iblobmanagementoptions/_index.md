---  
title: IBlobManagementOptions  
second_title: Aspose.Slides for Java API Reference  
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.  
type: docs  
url: /el/com.aspose.slides/iblobmanagementoptions/  
---```
public interface IBlobManagementOptions
```

Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα που αποθηκεύονται ως μια ενιαία οντότητα - δηλαδή το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. Χρησιμοποιούνται διάφορες τεχνικές για βελτιστοποίηση της κατανάλωσης μνήμης κατά την εργασία με BLOBs - που είναι ήδη αποθηκευμένα στην παρουσίαση ή προστίθενται αργότερα προγραμματικά. Χρησιμοποιώντας [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) μπορείτε να αλλάξετε διαφορετικές πτυχές συμπεριφοράς σχετικά με τη διαχείριση των BLOBs για το [IPresentation](../../com.aspose.slides/ipresentation) διάστημα ζωής του αντικειμένου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Αυτή η ιδιότητα καθορίζει εάν μια Presentation κλάση μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια του διαστήματος ζωής του αντικειμένου. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Αυτή η ιδιότητα καθορίζει εάν μια Presentation κλάση μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια του διαστήματος ζωής του αντικειμένου. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Αυτή η ιδιότητα καθορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί δικαιώματα δημιουργίας αρχείων. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Αυτή η ιδιότητα καθορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί δικαιώματα δημιουργίας αρχείων. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Η ρίζα της διαδρομής όπου θα δημιουργηθούν τα προσωρινά αρχεία. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Η ρίζα της διαδρομής όπου θα δημιουργηθούν τα προσωρινά αρχεία. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Καθορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Καθορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Αυτή η ιδιότητα καθορίζει εάν μια Presentation κλάση μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια του διαστήματος ζωής του αντικειμένου. Εάν το αντικείμενο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια του διαστήματος ζωής της Presentation. Αυτό είναι ένα παράδειγμα:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Θα προκύψει IOException επειδή το pres.pptx είναι κλειδωμένο για τη διάρκεια ζωής της Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // μετά το αντικείμενο Presentation απελευθερωθεί, το αρχείο ξεκλειδώνεται και μπορεί να διαγραφεί
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Επιστρέφει:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Αυτή η ιδιότητα καθορίζει εάν μια Presentation κλάση μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια του διαστήματος ζωής του αντικειμένου. Εάν το αντικείμενο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια του διαστήματος ζωής της Presentation. Αυτό είναι ένα παράδειγμα:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Θα προκληθεί IOException επειδή το pres.pptx είναι κλειδωμένο για τη διάρκεια ζωής της Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // μετά το αντικείμενο Presentation να απελευθερωθεί, το αρχείο ξεκλειδώνεται και μπορεί να διαγραφεί
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

Αυτή η ιδιότητα καθορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί δικαιώματα δημιουργίας αρχείων.

--------------------

Όλα τα αρχεία θα διαγραφούν μετά το τέλος της εργασίας με την παρουσίαση.

**Επιστρέφει:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Αυτή η ιδιότητα καθορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί δικαιώματα δημιουργίας αρχείων.

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

Η ρίζα της διαδρομής όπου θα δημιουργηθούν τα προσωρινά αρχεία. Θα χρησιμοποιηθεί εξ ορισμού ο προσωρινός φάκελος του συστήματος. Η διαδικασία φιλοξενίας πρέπει να έχει δικαιώματα δημιουργίας αρχείων και φακέλων εκεί.

**Επιστρέφει:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Η ρίζα της διαδρομής όπου θα δημιουργηθούν τα προσωρινά αρχεία. Θα χρησιμοποιηθεί εξ ορισμού ο προσωρινός φάκελος του συστήματος. Η διαδικασία φιλοξενίας πρέπει να έχει δικαιώματα δημιουργίας αρχείων και φακέλων εκεί.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Καθορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Από προεπιλογή, όλα τα BLOBs φορτώνονται στη μνήμη· μόνο όταν αυτό το όριο επιτευχθεί χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση, αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτήν την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας.

--------------------

Αυτή η ιδιότητα αγνοείται εάν \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) είναι ορισμένη σε false, επειδή η μνήμη είναι τότε η μόνη διαθέσιμη τοποθεσία αποθήκευσης και ο περιορισμός της χρήσης BLOBs στη μνήμη δεν έχει αποτέλεσμα.

--------------------

Η προεπιλεγμένη τιμή είναι 629 145 600 bytes (600 MB).

--------------------

Μπορείτε να ορίσετε αυτήν την ιδιότητα σε μηδέν, αλλά θα διατεθεί ακόμη ένας μικρός ελάχιστος όγκος μνήμης.

**Επιστρέφει:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Καθορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Από προεπιλογή, όλα τα BLOBs φορτώνονται στη μνήμη· μόνο όταν αυτό το όριο επιτευχθεί χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση, αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτήν την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας.

--------------------

Αυτή η ιδιότητα αγνοείται εάν \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) είναι ορισμένη σε false, επειδή η μνήμη είναι τότε η μόνη διαθέσιμη τοποθεσία αποθήκευσης και ο περιορισμός της χρήσης BLOBs στη μνήμη δεν έχει αποτέλεσμα.

--------------------

Η προεπιλεγμένη τιμή είναι 629 145 600 bytes (600 MB).

--------------------

Μπορείτε να ορίσετε αυτήν την ιδιότητα σε μηδέν, αλλά θα διατεθεί ακόμη ένας μικρός ελάχιστος όγκος μνήμης.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |