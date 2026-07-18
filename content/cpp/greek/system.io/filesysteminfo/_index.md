---
title: FileSystemInfo
second_title: Aspose.Slides για την Αναφορά API C++
description: "Η κλάση βάσης για FileInfo και DirectoryInfo. Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 300
url: /el/system.io/filesysteminfo/
---
## FileSystemInfo κλάση

Η κλάση βάσης για [FileInfo](../fileinfo/) και [DirectoryInfo](../directoryinfo/). Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε στις συναρτήσεις ως όρισμα.

```cpp
class FileSystemInfo : public System::Object
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| virtual void [Delete](./delete/)() | Διαγράφει το αντικείμενο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual void [Finalize](./finalize/)() | Δεν κάνει τίποτα. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | Επιστρέφει τα χαρακτηριστικά του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | Επιστρέφει την ημερομηνία δημιουργίας του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | Επιστρέφει την ημερομηνία δημιουργίας του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| virtual **bool** [get_Exists](./get_exists/)() | Καθορίζει εάν υπάρχει το αντικείμενο που αναφέρεται από τη διαδρομή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | Επιστρέφει την επέκταση του αρχείου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | Επιστρέφει το πλήρες όνομα (συμπεριλαμβανομένης της διαδρομής) του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | Επιστρέφει την τελευταία ώρα πρόσβασης του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Επιστρέφει την τελευταία ώρα πρόσβασης του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | Επιστρέφει την τελευταία ώρα εγγραφής του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Επιστρέφει την τελευταία ώρα εγγραφής του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Επιστρέφει ένα όνομα του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει τη δήλωση κλειδώματος C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση του string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση των strings. |
| void [Refresh](./refresh/)() | Ανανεώνει την κατάσταση του τρέχοντος αντικειμένου. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | Ορίζει τα καθορισμένα χαρακτηριστικά στο αντικείμενο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | Ορίζει την τελευταία ώρα πρόσβασης του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Ορίζει την τελευταία ώρα πρόσβασης του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | Ορίζει την τελευταία ώρα εγγραφής του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως τοπική ώρα. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Ορίζει την τελευταία ώρα εγγραφής του αντικειμένου που αντιπροσωπεύεται από το τρέχον αντικείμενο ως ώρα UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινή). Επιτρέπει την αλλαγή δείκτες σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την απελευθέρωση της δήλωσης κλειδώματος C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)