---
title: Details_MemberAccessException
second_title: Aspose.Slides για C++ API Αναφορά
description: "MemberAccessException αποβάλλεται όταν επιχειρείται πρόσβαση σε μέλος κλάσης που δεν υπάρχει ή όταν η πρόσβαση στο μέλος δεν επιτρέπεται. Ποτέ μην δημιουργείτε στιγμιότυπα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση MemberAccessException αντί αυτού. Ποτέ μην περιβάλλετε τα στιγμιότυπα της κλάσης MemberAccessException σε System::SmartPtr."
type: docs
weight: 547
url: /el/system/details_memberaccessexception/
---
## Details_MemberAccessException κλάση


MemberAccessException αποβάλλεται όταν επιχειρείται πρόσβαση σε μέλος κλάσης που δεν υπάρχει ή όταν η πρόσβαση στο μέλος δεν επιτρέπεται. Ποτέ μην δημιουργείτε στιγμιότυπα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση MemberAccessException αντί αυτού. Ποτέ μην περιβάλλετε τα στιγμιότυπα της κλάσης MemberAccessException σε [System::SmartPtr](../smartptr/).

```cpp
class Details_MemberAccessException : public System::Details_SystemException
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Επιστρέφει λεξικό με προσαρμοσμένα δεδομένα εξαίρεσης. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Επιστρέφει μια 32-bit ακέραια τιμή που είναι κωδικός HRESULT σχετικός με την εξαίρεση που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Επιστρέφει μια αναφορά στο αντικείμενο που αντιπροσωπεύει την εσωτερική εξαίρεση. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει την περιγραφή του σφάλματος. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει το ίχνος της στοίβας. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Επιστρέφει αντίγραφο του αντικειμένου Exception που αντιπροσωπεύει την πιο εσωτερική εξαίρεση. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Εφαρμόζει την κλειδώση της δήλωσης C# lock(). Κλήστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή σε υποκλάσεις. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Ορίζει το HRESULT, μια κωδικοποιημένη αριθμητική τιμή που εκχωρείται σε μια συγκεκριμένη εξαίρεση. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό ορίσμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηση. Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Επιστρέφει την συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Κλήστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδυνατισμένο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδυνατισμένο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Εφαρμόζει τη μέθοδο [what()](../details_exception/what/) που καλείται από την κλάση [ExceptionWrapper](../exceptionwrapper/). Παρά το γεγονός ότι αυτή η κλάση δεν κληρονομείται από std::exception, οι παράγωγες κλάσεις μπορούν να χρησιμοποιήσουν προστατευμένα/ιδιωτικά μέλη για την υλοποίηση της λογικής τους. Η μεταφορά της υλοποίησης αυτής της μεθόδου στο [ExceptionWrapper](../exceptionwrapper/) μπορεί να σπάσει αυτή τη λογική. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [Details_SystemException](../details_systemexception/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)