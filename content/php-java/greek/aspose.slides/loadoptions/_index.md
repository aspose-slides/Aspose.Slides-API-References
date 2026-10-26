---
title: LoadOptions
second_title: Aspose.Sildes για PHP μέσω Αναφοράς API Java
description: 
type: docs
url: /el/aspose.slides/loadoptions/
---
## LoadOptions κλάση

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.

### LoadOptions {#LoadOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| LoadOptions() | Δημιουργεί νέες προεπιλεγμένες επιλογές φόρτωσης. |

**Επιστρέφει:**
LoadOptions

---

### LoadOptions {#LoadOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| LoadOptions(int) | Δημιουργεί νέες επιλογές φόρτωσης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| loadFormat | int | Μορφή της παρουσίασης προς φόρτωση. |

**Επιστρέφει:**
LoadOptions

---

### getBlobManagementOptions {#getBlobManagementOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| getBlobManagementOptions () | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται να διαμορφώσουν την καλύτερη αναλογία απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μία ενιαία οντότητα - δηλαδή το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. |

**Επιστρέφει:**
[BlobManagementOptions](../blobmanagementoptions)

---

### getDefaultAsianFont {#getDefaultAsianFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefaultAsianFont () | Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String

---

### getDefaultRegularFont {#getDefaultRegularFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefaultRegularFont () | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String

---

### getDefaultSymbolFont {#getDefaultSymbolFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefaultSymbolFont () | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String

---

### getDefaultTextLanguage {#getDefaultTextLanguage}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefaultTextLanguage () | Επιστρέφει ή ορίζει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String

---

### getDeleteEmbeddedBinaryObjects {#getDeleteEmbeddedBinaryObjects}

| Όνομα | Περιγραφή |
| --- | --- |
| getDeleteEmbeddedBinaryObjects () | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων: Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
boolean

---

### getDocumentLevelFontSources {#getDocumentLevelFontSources}

| Όνομα | Περιγραφή |
| --- | --- |
| getDocumentLevelFontSources () | Καθορίζει τις πηγές εξωτερικών γραμματοσειρών που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ’ όλη τη διάρκεια της ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις. |

**Επιστρέφει:**
[FontSources](../fontsources)

---

### getInterruptionToken {#getInterruptionToken}

| Όνομα | Περιγραφή |
| --- | --- |
| getInterruptionToken () | Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής. Αυτό το διακριτικό διαχειρίζεται όλη τη διάρκεια ζωής του παραδείγματος IPresentation. Οποιαδήποτε μακρά διεργασία, όπως η φόρτωση ή η αποθήκευση μιας παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου InterruptionTokenSource#interrupt του InterruptionTokenSource. |

**Επιστρέφει:**
[InterruptionToken](../interruptiontoken)

---

### getLoadFormat {#getLoadFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getLoadFormat () | Επιστρέφει ή ορίζει τη μορφή της παρουσίασης προς φόρτωση. Ανάγνωση/εγγραφή LoadFormat. |

**Επιστρέφει:**
int

---

### getOnlyLoadDocumentProperties {#getOnlyLoadDocumentProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getOnlyLoadDocumentProperties () | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης. Η τιμή true σημαίνει ότι θα φορτωθούν μόνο οι ιδιότητες εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρόσβασης θα αγνοηθεί. Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση θα φορτωθεί με χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή ιδιότητας είναι true, τότε οι ιδιότητες εγγράφου δεν μπορούν να φορτωθούν και θα προκληθεί εξαίρεση. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getPassword {#getPassword}

| Όνομα | Περιγραφή |
| --- | --- |
| getPassword () | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση/εγγραφή String. Τιμή: Ο κωδικός πρόσβασης. |

**Επιστρέφει:**
String

---

### getResourceLoadingCallback {#getResourceLoadingCallback}

| Όνομα | Περιγραφή |
| --- | --- |
| getResourceLoadingCallback () | Επιστρέφει ή ορίζει το interface callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή IResourceLoadingCallback. |

**Επιστρέφει:**
SvgResourceResolver, ResourceLoadingAdapter

---

### getSpreadsheetOptions {#getSpreadsheetOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| getSpreadsheetOptions () | Λαμβάνει επιλογές για φύλλα εργασίας. Για παράδειγμα, αυτές οι επιλογές επηρεάζουν τον υπολογισμό τύπων για γραφήματα. |

**Επιστρέφει:**
[SpreadsheetOptions](../spreadsheetoptions)

---

### getWarningCallback {#getWarningCallback}

| Όνομα | Περιγραφή |
| --- | --- |
| getWarningCallback () | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. Ανάγνωση/εγγραφή IWarningCallback. |

**Επιστρέφει:**
IWarningCallback

---

### setBlobManagementOptions {#setBlobManagementOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| setBlobManagementOptions ([BlobManagementOptions](../blobmanagementoptions)) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται να διαμορφώσουν την καλύτερη αναλογία απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μία ενιαία οντότητα - δηλαδή το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. |

**Επιστρέφει:**
void

---

### setDefaultAsianFont {#setDefaultAsianFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setDefaultAsianFont (String) | Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void

---

### setDefaultRegularFont {#setDefaultRegularFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setDefaultRegularFont (String) | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void

---

### setDefaultSymbolFont {#setDefaultSymbolFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setDefaultSymbolFont (String) | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται σε περίπτωση που δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void

---

### setDefaultTextLanguage {#setDefaultTextLanguage}

| Όνομα | Περιγραφή |
| --- | --- |
| setDefaultTextLanguage (String) | Επιστρέφει ή ορίζει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void

---

### setDeleteEmbeddedBinaryObjects {#setDeleteEmbeddedBinaryObjects}

| Όνομα | Περιγραφή |
| --- | --- |
| setDeleteEmbeddedBinaryObjects (boolean) | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων: Ανάγνωση/εγγραφή boolean. Η προεπιλογή είναι false. |

**Επιστρέφει:**
void

---

### setDocumentLevelFontSources {#setDocumentLevelFontSources}

| Όνομα | Περιγραφή |
| --- | --- |
| setDocumentLevelFontSources ([FontSources](../fontsources)) | Καθορίζει τις πηγές εξωτερικών γραμματοσειρών που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ’ όλη τη διάρκεια της ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις. |

**Επιστρέφει:**
void

---

### setInterruptionToken {#setInterruptionToken}

| Όνομα | Περιγραφή |
| --- | --- |
| setInterruptionToken ([InterruptionToken](../interruptiontoken)) | Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής. Αυτό το διακριτικό διαχειρίζεται όλη τη διάρκεια ζωής του παραδείγματος IPPresentation. Οποιαδήποτε μακρά διεργασία, όπως η φόρτωση ή η αποθήκευση μιας παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου InterruptionTokenSource#interrupt του InterruptionTokenSource. |

**Επιστρέφει:**
void

---

### setLoadFormat {#setLoadFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setLoadFormat (int) | Επιστρέφει ή ορίζει τη μορφή της παρουσίασης προς φόρτωση. Ανάγνωση/εγγραφή LoadFormat. |

**Επιστρέφει:**
void

---

### setOnlyLoadDocumentProperties {#setOnlyLoadDocumentProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| setOnlyLoadDocumentProperties (boolean) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης. Η τιμή true σημαίνει ότι θα φορτωθούν μόνο οι ιδιότητες εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρόσβασης θα αγνοηθεί. Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση θα φορτωθεί με χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή ιδιότητας είναι true, τότε οι ιδιότητες εγγράφου δεν μπορούν να φορτωθούν και θα προκληθεί εξαίρεση. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setPassword {#setPassword}

| Όνομα | Περιγραφή |
| --- | --- |
| setPassword (String) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση/εγγραφή String. Τιμή: Ο κωδικός πρόσβασης. |

**Επιστρέφει:**
void

---

### setResourceLoadingCallback {#setResourceLoadingCallback}

| Όνομα | Περιγραφή |
| --- | --- |
| setResourceLoadingCallback ([IResourceLoadingCallback](../iresourceloadingcallback)) | Επιστρέφει ή ορίζει το interface callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή IResourceLoadingCallback. |

**Επιστρέφει:**
void

---

### setSpreadsheetOptions {#setSpreadsheetOptions}

| Όνομα | Περιγραφή |
| --- | --- |
| setSpreadsheetOptions ([SpreadsheetOptions](../spreadsheetoptions)) | Λαμβάνει επιλογές για φύλλα εργασίας. Για παράδειγμα, αυτές οι επιλογές επηρεάζουν τον υπολογισμό τύπων για γραφήματα. |

**Επιστρέφει:**
void

---

### setWarningCallback {#setWarningCallback}

| Όνομα | Περιγραφή |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. Ανάγνωση/εγγραφή IWarningCallback. |

**Επιστρέφει:**
void

---