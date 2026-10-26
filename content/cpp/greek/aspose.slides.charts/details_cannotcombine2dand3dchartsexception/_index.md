---
title: Details_CannotCombine2DAnd3DChartsException
second_title: Aspose.Slides για C++ API Αναφορά
description: Εξαίρεση που ρίχνεται όταν προσπαθείτε να συνδυάσετε τύπους διαγραμμάτων 2D και 3D.
type: docs
weight: 443
url: /el/aspose.slides.charts/details_cannotcombine2dand3dchartsexception/
---
## Details_CannotCombine2DAnd3DChartsException κλάση

Εξαίρεση που ρίχνεται όταν προσπαθείτε να συνδυάσετε τύπους διαγραμμάτων 2D και 3D.

```cpp
class Details_CannotCombine2DAnd3DChartsException : public System::Details_InvalidOperationException
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaNs θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaNs θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Επιστρέφει λεξικό με προσαρμοσμένα δεδομένα εξαίρεσης. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Επιστρέφει μια τιμή ακεραίου 32-bit η οποία είναι κωδικός HRESULT που σχετίζεται με την εξαίρεση που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Επιστρέφει μια αναφορά στο αντικείμενο που αντιπροσωπεύει την εσωτερική εξαίρεση. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Επιστρέφει το συμβολοσειρά που περιέχει την περιγραφή του σφάλματος. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Επιστρέφει τη συμβολοσειρά που περιέχει το ίχνος στοίβας. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Επιστρέφει ένα αντίγραφο του αντικειμένου Exception που αντιπροσωπεύει την πιο εσωτερική εξαίρεση. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_invalidoperationexception/gettype/)() const override | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_invalidoperationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα (lock()) της δήλωσης C#. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκλάσεων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκλάσεων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Ορίζει το HRESULT, μια κωδικοποιημένη αριθμητική τιμή που εκχωρείται σε συγκεκριμένη εξαίρεση. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'ο όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Επιστρέφει την αναπαράσταση συμβολοσειράς του τρέχοντος αντικειμένου. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_invalidoperationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εκδίπλωση (unlock()) της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Υλοποιεί τη μέθοδο [what()](../../system/details_exception/what/) που καλείται από την κλάση [ExceptionWrapper](../../system/exceptionwrapper/). Παρά το γεγονός ότι αυτή η κλάση δεν κληρονομεί από std::exception, παράγωγες κλάσεις μπορούν να χρησιμοποιήσουν προστατευμένα/ιδιωτικά μέλη για να υλοποιήσουν τη λογική τους. Η μεταφορά της υλοποίησης αυτής της μεθόδου στο [ExceptionWrapper](../../system/exceptionwrapper/) μπορεί να σπάσει αυτή τη λογική. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Details_InvalidOperationException](../../system/details_invalidoperationexception/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)