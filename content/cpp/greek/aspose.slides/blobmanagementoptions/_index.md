---
title: BlobManagementOptions
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση κανόνων χειρισμού BLOB και άλλων ρυθμίσεων BLOB.
type: docs
weight: 196
url: /el/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions κλάση

Αναπαριστά επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση κανόνων χειρισμού BLOB και άλλων ρυθμίσεων BLOB.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Δημιουργεί νέες προεπιλεγμένες επιλογές διαχείρισης BLOB. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Αυτή η ιδιότητα ορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά τη δουλειά με BLOBs, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί δικαιώματα για δημιουργία αρχείων. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Ορίζει το μέγιστο συνολικό μέγεθος (σε byte) που επιτρέπεται να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Από προεπιλογή, όλα τα BLOBs φορτώνονται στη μνήμη· μόνο όταν επιτευχθεί αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να προκαλέσει υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτή την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Αυτή η ιδιότητα ορίζει εάν μια παρουσία της κλάσης [Presentation](../presentation/) μπορεί να είναι ιδιοκτήτης της πηγής – αρχείου ή ροής – κατά τη διάρκεια του κύκλου ζωής της παρουσίας. Εάν η παρουσία είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της χρήσης μνήμης και της απόδοσης κατά τη δουλειά με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια του κύκλου ζωής του [Presentation](../presentation/). |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Ο προσωρινός κατάλογος [System](../../system/) θα χρησιμοποιηθεί από προεπιλογή. Η διαδικασία φιλοξενίας πρέπει να έχει δικαιώματα δημιουργίας αρχείων και φακέλων εκεί. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορικά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Αυτή η ιδιότητα ορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά τη δουλειά με BLOBs, κάτι που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί δικαιώματα για δημιουργία αρχείων. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Ορίζει το μέγιστο συνολικό μέγεθος (σε byte) που επιτρέπεται να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Από προεπιλογή, όλα τα BLOBs φορτώνονται στη μνήμη· μόνο όταν επιτευχθεί αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να προκαλέσει υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτή την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Αυτή η ιδιότητα ορίζει εάν μια παρουσία της κλάσης [Presentation](../presentation/) μπορεί να είναι ιδιοκτήτης της πηγής – αρχείου ή ροής – κατά τη διάρκεια του κύκλου ζωής της παρουσίας. Εάν η παρουσία είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της χρήσης μνήμης και της απόδοσης κατά τη δουλειά με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια του κύκλου ζωής του [Presentation](../presentation/). |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Ο προσωρινός κατάλογος [System](../../system/) θα χρησιμοποιηθεί από προεπιλογή. Η διαδικασία φιλοξενίας πρέπει να έχει δικαιώματα δημιουργίας αρχείων και φακέλων εκεί. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδρή δεικτό (αντί για κοινή). Επιτρέπει τη μετατροπή δεικτών σε συλλογές σε αδρή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει τη τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τον κατασκευαστή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδρό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδρό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IBlobManagementOptions](../iblobmanagementoptions/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)