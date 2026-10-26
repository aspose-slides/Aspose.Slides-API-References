---
title: ILoadOptions
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών, όπως μορφή ή προεπιλεγμένη γραμματοσειρά, κατά τη φόρτωση μιας παρουσίασης.
type: docs
url: /el/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. |
| [getPassword()](#getPassword--) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης. |
| [getWarningCallback()](#getWarningCallback--) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς επεξεργασίας Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB στη μνήμη. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς επεξεργασίας Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB στη μνήμη. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. |
| [getInterruptionToken()](#getInterruptionToken--) | Το διακριτικό για παρακολούθηση αιτημάτων διακοπής. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Το διακριτικό για παρακολούθηση αιτημάτων διακοπής. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Επιστρέφει ή ορίζει τη διεπαφή callback η οποία διαχειρίζεται τη φόρτωση εξωτερικών πόρων. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Επιστρέφει ή ορίζει τη διεπαφή callback η οποία διαχειρίζεται τη φόρτωση εξωτερικών πόρων. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό πρόσθετης συμπεριφοράς υπολογιστικών φύλλων. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό πρόσθετης συμπεριφοράς υπολογιστικών φύλλων. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. Ανάγνωση/εγγραφή [LoadFormat](../../com.aspose.slides/loadformat).

**Επιστρέφει:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. Ανάγνωση/εγγραφή [LoadFormat](../../com.aspose.slides/loadformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση-εγγραφή String.

Τιμή: Ο κωδικός πρόσβασης.

**Επιστρέφει:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση-εγγραφή String.

Τιμή: Ο κωδικός πρόσβασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης. Η τιμή true σημαίνει ότι πρέπει να φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρόσβασης θα αγνοηθεί. Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με τη χρήση του σωστού κωδικού πρόσβασης. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, τότε δεν μπορούν να φορτωθούν οι ιδιότητες του εγγράφου και θα προκληθεί εξαίρεση. Ανάγνωση-εγγραφή boolean.

**Επιστρέφει:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης. Η τιμή true σημαίνει ότι πρέπει να φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρόσβασης θα αγνοηθεί. Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με τη χρήση του σωστού κωδικού πρόσβασης. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, τότε δεν μπορούν να φορτωθούν οι ιδιότητες του εγγράφου και θα προκληθεί εξαίρεση. Ανάγνωση-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Ανάγνωση/εγγραφή [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Επιστρέφει:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Ανάγνωση/εγγραφή [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς επεξεργασίας Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται να καθορίσουν την καλύτερη σχέση απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις.

--------------------

Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μία οντότητα – π.χ. το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση.

**Επιστρέφει:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς επεξεργασίας Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται να καθορίσουν την καλύτερη σχέση απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις.

--------------------

Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μία οντότητα – π.χ. το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη της τη διάρκεια και δεν μοιράζονται με άλλες παρουσιάσεις.

**Επιστρέφει:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη της τη διάρκεια και δεν μοιράζονται με άλλες παρουσιάσεις.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Το διακριτικό για παρακολούθηση αιτημάτων διακοπής.

--------------------

Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια του [IPresentation](../../com.aspose.slides/ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση ή η αποθήκευση παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) του [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Επιστρέφει:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Το διακριτικό για παρακολούθηση αιτημάτων διακοπής.

--------------------

Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια του [IPresentation](../../com.aspose.slides/ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση ή η αποθήκευση παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) του [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Επιστρέφει ή ορίζει τη διεπαφή callback η οποία διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Επιστρέφει:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Επιστρέφει ή ορίζει τη διεπαφή callback η οποία διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό πρόσθετης συμπεριφοράς υπολογιστικών φύλλων.

**Επιστρέφει:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό πρόσθετης συμπεριφοράς υπολογιστικών φύλλων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String.

--------------------

> ```
> Example:
>   
>  // Χρησιμοποιήστε τις επιλογές φόρτωσης για να ορίσετε την προεπιλεγμένη γλώσσα κειμένου
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Προσθέστε νέο σχήμα ορθογωνίου με κείμενο
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Ελέγξτε τη γλώσσα του πρώτου τμήματος
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.

Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων:

 *  
 *  
 *  

Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.

Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων:

 *  
 *  
 *  

Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε την παρουσίαση χωρίς ενσωματωμένα δυαδικά αντικείμενα.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |