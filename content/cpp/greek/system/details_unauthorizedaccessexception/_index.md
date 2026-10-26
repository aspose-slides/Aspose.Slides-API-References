---
title: Details_UnauthorizedAccessException
second_title: Aspose.Slides για C++ API Αναφορά
description: "Το UnauthorizedAccessException ρίχνεται όταν η πρόσβαση απορρίπτεται από το λειτουργικό σύστημα λόγω σφάλματος I/O ή σφάλματος ασφαλείας. Μην δημιουργείτε ποτέ στιγμιότυπα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση UnauthorizedAccessException αντί αυτού. Μην τοποθετείτε ποτέ τις στιγμιότυπα της κλάσης UnauthorizedAccessException σε System::SmartPtr."
type: docs
weight: 755
url: /el/system/details_unauthorizedaccessexception/
---
## Details_UnauthorizedAccessException κλάση

Το UnauthorizedAccessException ρίχνεται όταν η πρόσβαση απορρίπτεται από το λειτουργικό σύστημα λόγω σφάλματος I/O ή σφάλματος ασφαλείας. Μην δημιουργείτε ποτέ στιγμιότυπα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση UnauthorizedAccessException αντί αυτού. Μην τοποθετείτε ποτέ τις στιγμιότυπα της κλάσης UnauthorizedAccessException σε [System::SmartPtr](../smartptr/).

```cpp
class Details_UnauthorizedAccessException : public System::Details_SystemException
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Για εσωτερική χρήση μόνο. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Επιστρέφει λεξικό με προσαρμοσμένα δεδομένα εξαίρεσης. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Επιστρέφει μια τιμή 32-bit ακέραιου που είναι κωδικός HRESULT σχετικός με την εξαίρεση που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Επιστρέφει μια αναφορά στο αντικείμενο που αντιπροσωπεύει την εσωτερική εξαίρεση. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει την περιγραφή του σφάλματος. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει το stack trace. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Επιστρέφει αντίγραφο του αντικειμένου Exception που αντιπροσωπεύει την πιο εσωτερική εξαίρεση. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Χρειάζεται τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Ενεργοποιεί την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Υλοποιεί την εντολή C# lock() για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περιπτώσεις συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περιπτώσεις συμβολοσειρών. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Ορίζει το HRESULT, μια κωδικοποιημένη αριθμητική τιμή που εκχωρείται σε συγκεκριμένη εξαίρεση. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την εναλλαγή δείκτες σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Επιστρέφει τη συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Υλοποιεί τη μέθοδο [what()](../details_exception/what/) η οποία καλείται από την κλάση [ExceptionWrapper](../exceptionwrapper/). Παρά το γεγονός ότι αυτή η κλάση δεν κληρονομείται από std::exception, οι παράγωγες κλάσεις μπορούν να χρησιμοποιήσουν προστατευμένα/ιδιωτικά μέλη για την υλοποίηση της λογικής τους. Η μετακίνηση αυτής της υλοποίησης στη [ExceptionWrapper](../exceptionwrapper/) μπορεί να σπάσει αυτή τη λογική. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Details_SystemException](../details_systemexception/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)