---
title: Details_CultureNotFoundException
second_title: Αναφορά API Aspose.Slides για C++
description: "CultureNotFoundException εμφανίζεται όταν γίνεται προσπάθεια να δημιουργηθεί μια πολιτιστική ρύθμιση που δεν είναι διαθέσιμη. Ποτέ μην δημιουργείτε παραδείγματα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση CultureNotFoundException αντί αυτού. Ποτέ μην ενσωματώνετε τα παραδείγματα της κλάσης CultureNotFoundException μέσα στο System::SmartPtr."
type: docs
weight: 92
url: /el/system.globalization/details_culturenotfoundexception/
---
## Details_CultureNotFoundException κλάση


CultureNotFoundException εμφανίζεται όταν γίνεται προσπάθεια να δημιουργηθεί μια πολιτιστική ρυθμίση που δεν είναι διαθέσιμη. Ποτέ μην δημιουργείτε παραδείγματα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση CultureNotFoundException αντί αυτού. Ποτέ μην ενσωματώνετε τα παραδείγματα της κλάσης CultureNotFoundException μέσα στο [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_CultureNotFoundException : public System::Details_ArgumentException
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Επιστρέφει λεξικό με προσαρμοσμένα δεδομένα εξαίρεσης. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Επιστρέφει μια 32-bit ακέραια τιμή που είναι κωδικός HRESULT σχετικός με την εξαίρεση που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Επιστρέφει μια αναφορά στο αντικείμενο που αντιπροσωπεύει την εσωτερική εξαίρεση. |
| virtual [Nullable](../../system/nullable/)\<int\> [get_InvalidCultureId](./get_invalidcultureid/)() const |  |
| virtual [String](../../system/string/) [get_InvalidCultureName](./get_invalidculturename/)() const |  |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει την περιγραφή του σφάλματος. |
| [String](../../system/string/) [get_ParamName](../../system/details_argumentexception/get_paramname/)() |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει το ίχνος στοίβας. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Επιστρέφει το αντίγραφο του αντικειμένου Exception που αντιπροσωπεύει την πιο εσωτερική εξαίρεση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_argumentexception/gettype/)() const override | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_argumentexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Ορίζει το HRESULT, μια κωδικοποιημένη αριθμητική τιμή που ανατίθεται σε μια συγκεκριμένη εξαίρεση. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Επιστρέφει την συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_argumentexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Υλοποιεί τη μέθοδο [what()](../../system/details_exception/what/) που καλείται από την κλάση [ExceptionWrapper](../../system/exceptionwrapper/). Παρά το γεγονός ότι αυτή η κλάση δεν κληρονομείται από std::exception, οι παράγωγες κλάσεις μπορούν να χρησιμοποιήσουν προστατευμένα/ιδιωτικά μέλη για να υλοποιήσουν τη λογική τους. Η μετακίνηση της υλοποίησης αυτής της μεθόδου στο [ExceptionWrapper](../../system/exceptionwrapper/) μπορεί να σπάσει αυτή τη λογική. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [Details_ArgumentException](../../system/details_argumentexception/)
* Ονομαχώρος [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)