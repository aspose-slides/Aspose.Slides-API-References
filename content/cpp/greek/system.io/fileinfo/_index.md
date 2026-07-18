---
title: FileInfo
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεί μια διαδρομή σε αρχείο και ένα αρχείο που αναφέρεται από αυτή τη διαδρομή και παρέχει μεθόδους για τη διαχείρισή του. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο μέσω της συνάρτησης System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 274
url: /el/system.io/fileinfo/
---
## FileInfo κλάση

Αναπαριστά μια διαδρομή σε αρχείο και το αρχείο που αναφέρεται από αυτή τη διαδρομή και παρέχει μεθόδους για τη διαχείρισή του. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο μέσω της συνάρτησης [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να τη δώσετε σε συναρτήσεις ως όρισμα.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Μεθόδοι

| Method | Description |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Ανοίγει ένα αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο για εγγραφή κειμένου χρησιμοποιώντας κωδικοποίηση UTF-8, σε λειτουργία «Append» χωρίς διαμοιρασμό. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Αντιγράφει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη θέση. Εάν το αρχείο προορισμού υπάρχει ήδη, η αντιγραφή αποτυγχάνει. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Αντιγράφει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη θέση. Ένα παράμετρος καθορίζει αν το υπάρχον αρχείο προορισμού πρέπει να αντικατασταθεί. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Δημιουργεί ένα αρχείο στην τοποθεσία που καθορίζεται από τη διαδρομή του τρέχοντος αντικειμένου και το ανοίγει για ανάγνωση και εγγραφή, σε λειτουργία περικοπής και χωρίς διαμοιρασμό. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Δημιουργεί ένα αρχείο στην τοποθεσία που καθορίζεται από τη διαδρομή του τρέχοντος αντικειμένου και το ανοίγει για εγγραφή κειμένου χρησιμοποιώντας κωδικοποίηση UTF-8 χωρίς διαμοιρασμό. |
| void [Decrypt](./decrypt/)() | NOT IMPLEMENTED. |
| void [Delete](./delete/)() override | Αφαιρεί το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [Encrypt](./encrypt/)() | NOT IMPLEMENTED. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Κατασκευάζει μια νέα παρουσία της κλάσης [FileInfo](./) που αντιπροσωπεύει το καθορισμένο αρχείο. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Δεν κάνει τίποτα. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Επιστρέφει τα χαρακτηριστικά της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Επιστρέφει την ώρα δημιουργίας της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Επιστρέφει την ώρα δημιουργίας της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Επιστρέφει ένα αντικείμενο [DirectoryInfo](../directoryinfo/) που αντιπροσωπεύει έναν φάκελο στον οποίο βρίσκεται το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Επιστρέφει το πλήρες όνομα του φακέλου στον οποίο βρίσκεται το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [get_Exists](./get_exists/)() override | Επιστρέφει μια τιμή που υποδεικνύει αν το αρχείο υπάρχει. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Επιστρέφει την επέκταση του αρχείου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Επιστρέφει το πλήρες όνομα (συμπεριλαμβανομένης της διαδρομής) της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Επιστρέφει μια τιμή που υποδεικνύει αν το χαρακτηριστικό ReadOnly είναι ενεργό. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Επιστρέφει το χρόνο τελευταίας πρόσβασης της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Επιστρέφει το χρόνο τελευταίας πρόσβασης της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Επιστρέφει το χρόνο τελευταίας εγγραφής της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Επιστρέφει το χρόνο τελευταίας εγγραφής της οντότητας που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| **int64_t** [get_Length](./get_length/)() | Επιστρέφει το μέγεθος του αρχείου σε bytes. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Επιστρέφει το όνομα του αρχείου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# «is». |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Μετακινεί το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη θέση. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει πραγματικά τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή υποκατηγοριών με αντιγραφή. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Ανοίγει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη λειτουργία για ανάγνωση και εγγραφή και χωρίς διαμοιρασμό. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Ανοίγει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη λειτουργία, με τον καθορισμένο τύπο πρόσβασης και χωρίς διαμοιρασμό. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Ανοίγει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη λειτουργία, με τον καθορισμένο τύπο πρόσβασης και επιλογή διαμοιρασμού. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Ανοίγει ένα αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο μόνο για ανάγνωση, σε λειτουργία «Open» με διαμοιρασμένη πρόσβαση για ανάγνωση. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Ανοίγει το υπάρχον αρχείο στην τοποθεσία που καθορίζεται από τη διαδρομή του τρέχοντος αντικειμένου για ανάγνωση κειμένου χρησιμοποιώντας κωδικοποίηση UTF-8 χωρίς διαμοιρασμό. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Ανοίγει ένα αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο μόνο για εγγραφή, σε λειτουργία «OpenOrCreate» χωρίς διαμοιρασμό. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει πραγματικά τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή υποκατηγοριών με αντιγραφή. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr με αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| void [Refresh](../filesysteminfo/refresh/)() | Ανανέuje την κατάσταση του τρέχοντος αντικειμένου. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Αντικαθιστά τα περιεχόμενα ενός καθορισμένου αρχείου προορισμού με το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο [FileInfo](./) και δημιουργεί αντίγραφο ασφαλείας του αντικατεστημένου αρχείου. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Αντικαθιστά τα περιεχόμενα ενός καθορισμένου αρχείου προορισμού με το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο [FileInfo](./) και δημιουργεί αντίγραφο ασφαλείας του αντικατεστημένου αρχείου. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Ορίζει τα καθορισμένα χαρακτηριστικά στην οντότητα που αναπαριστά το τρέχον αντικείμενο. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας της οντότητας που αναπαριστά το τρέχον αντικείμενο ως τοπική ώρα. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας της οντότητας που αναπαριστά το τρέχον αντικείμενο ως ώρα UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Ορίζει ή αφαιρεί το χαρακτηριστικό ReadOnly στο αρχείο. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Ορίζει το χρόνο τελευταίας πρόσβασης της οντότητας που αναπαριστά το τρέχον αντικείμενο ως τοπική ώρα. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Ορίζει το χρόνο τελευταίας πρόσβασης της οντότητας που αναπαριστά το τρέχον αντικείμενο ως ώρα UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Ορίζει το χρόνο τελευταίας εγγραφής της οντότητας που αναπαριστά το τρέχον αντικείμενο ως τοπική ώρα. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Ορίζει το χρόνο τελευταίας εγγραφής της οντότητας που αναπαριστά το τρέχον αντικείμενο ως ώρα UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (και όχι κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Επιστρέφει μια διαδρομή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του statement lock() της C#. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [FileSystemInfo](../filesysteminfo/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)