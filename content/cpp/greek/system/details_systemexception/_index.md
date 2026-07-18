---
title: Details_SystemException
second_title: Αναφορά API Aspose.Slides για C++
description: "Μια βασική κλάση για κλάσεις που αντιπροσωπεύουν εξαιρέσεις συστήματος (και όχι εφαρμογής). Ποτέ μην δημιουργείτε στιγμιότυπα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση SystemException αντί αυτού. Ποτέ μην περιβάλλετε τα στιγμιότυπα της κλάσης SystemException σε System::SmartPtr."
type: docs
weight: 703
url: /el/system/details_systemexception/
---
## Details_SystemException κλάση

Μια βασική κλάση για κλάσεις που αντιπροσωπεύουν εξαιρέσεις συστήματος (και όχι εφαρμογής). Ποτέ μην δημιουργείτε στιγμιότυπα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε αντί αυτού την κλάση SystemException. Ποτέ μην περιβάλλετε τα στιγμιότυπα της κλάσης SystemException στο [System::SmartPtr](../smartptr/).

```cpp
class Details_SystemException : public System::Details_Exception
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Επιστρέφει λεξικό με προσαρμοσμένα δεδομένα εξαίρεσης. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Επιστρέφει μια τιμή 32-bit ακεραίου που είναι κώδικας HRESULT συνδεδεμένος με την εξαίρεση που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Επιστρέφει μία αναφορά στο αντικείμενο που αντιπροσωπεύει την εσωτερική εξαίρεση. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει την περιγραφή σφάλματος. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει το ίχνος στοίβας. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Επιστρέφει ένα αντίγραφο του αντικειμένου Exception που αντιπροσωπεύει την πιο εσωτερική εξαίρεση. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Ενεργοποιεί την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Λαμβάνει τον τρέχοντα τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, μόνο αρχικοποιεί το νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, μόνο αρχικοποιεί το νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Ορίζει το HRESULT, μια κωδικοποιημένη αριθμητική τιμή που αντιστοιχίζεται σε συγκεκριμένη εξαίρεση. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό ορίσμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Επιστρέφει την συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Υλοποιεί την ανετοποίηση της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτοδείκτες ή ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Υλοποιεί τη μέθοδο [what()](../details_exception/what/) που καλείται από την κλάση [ExceptionWrapper](../exceptionwrapper/). Παρά το γεγονός ότι αυτή η κλάση δεν κληρονομεί από std::exception, οι παράγωγες κλάσεις μπορούν να χρησιμοποιήσουν προστατευμένα/ιδιωτικά μέλη για να υλοποιήσουν τη λογική τους. Η μεταφορά της υλοποίησης αυτής της μεθόδου στο [ExceptionWrapper](../exceptionwrapper/) μπορεί να διασπάσει αυτή τη λογική. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Details_Exception](../details_exception/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)