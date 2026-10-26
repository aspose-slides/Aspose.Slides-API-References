---
title: IBackdrop3DScene
second_title: Αναφορά API του Aspose.Slides για C++
description: Ορίζει ένα επίπεδο στο οποίο εφαρμόζονται εφέ, όπως λάμψη και σκιά, σε σχέση με το σχήμα στο οποίο εφαρμόζονται.
type: docs
weight: 1392
url: /el/aspose.slides/ibackdrop3dscene/
---
## IBackdrop3DScene κλάση


Defines a plane in which effects, such as glow and shadow, are applied in relation to the shape they are being applied to.

```cpp
class IBackdrop3DScene : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας C# [Object.Equals](../../system/object/equals/) συμβατότητες. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρ'όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρ'όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() | Επιστρέφει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στο χώρο που αγκιστρώνει το επίπεδο φόντου. Το τρισδιάστατο σημείο αντιπροσωπεύεται από πίνακα 3 τιμών τύπου **float** που ορίζουν τις συντεταγμένες X, Y και Z. Διαβάστε **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() | Επιστρέφει ένα διάνυσμα κανονικού. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα κάθετο στην όψη του επιπέδου φόντου. Το διάνυσμα αντιπροσωπεύεται από πίνακα 3 τιμών τύπου **float** που ορίζουν τις συντεταγμένες X, Y και Z. Διαβάστε **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() | Επιστρέφει ένα διάνυσμα που αντιπροσωπεύει την κατεύθυνση άνω. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα που αντιπροσωπεύει την κατεύθυνση άνω σε σχέση με την όψη του επιπέδου φόντου. Το διάνυσμα αντιπροσωπεύεται από πίνακα 3 τιμών τύπου **float** που ορίζουν τις συντεταγμένες X, Y και Z. Διαβάστε **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική του C# [Object.GetHashCode()](../../system/object/gethashcode/) μεθόδου. Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική του C# [System.Object.GetType()](../../system/object/gettype/) κλήσης. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογική του C# 'is' τελεστή. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση απευθείας ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική του C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) μεθόδου. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει την καταμέτρηση κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Ορίζει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στο χώρο που αγκιστρώνει το επίπεδο φόντου. Το τρισδιάστατο σημείο αντιπροσωπεύεται από πίνακα 3 τιμών τύπου **float** που ορίζουν τις συντεταγμένες X, Y και Z. Γράψτε **float**[]. |
| virtual void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Ορίζει ένα διάνυσμα κανονικού. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα κάθετο στην όψη του επιπέδου φόντου. Το διάνυσμα αντιπροσωπεύεται από πίνακα 3 τιμών τύπου **float** που ορίζουν τις συντεταγμένες X, Y και Z. Γράψτε **float**[]. |
| virtual void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Ορίζει ένα διάνυσμα που αντιπροσωπεύει την κατεύθυνση άνω. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα που αντιπροσωπεύει την κατεύθυνση άνω σε σχέση με την όψη του επιπέδου φόντου. Το διάνυσμα αντιπροσωπεύεται από πίνακα 3 τιμών τύπου **float** που ορίζουν τις συντεταγμένες X, Y και Z. Γράψτε **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυναμική λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή της καταμέτρησης κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει την καταμέτρηση κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει την καταμέτρηση κοινής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική του C# [Object.ToString()](../../system/object/tostring/) μεθόδου. Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση απευθείας ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει την καταμέτρηση αδυναμικής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει την καταμέτρηση αδυναμικής αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Ονομαχώρος [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)