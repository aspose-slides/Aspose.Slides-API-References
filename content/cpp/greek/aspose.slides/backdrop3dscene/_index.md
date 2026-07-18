---
title: Backdrop3DScene
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει ένα επίπεδο στο οποίο εφαρμόζονται εφέ, όπως λάμψη και σκιά, σε σχέση με το σχήμα στο οποίο εφαρμόζονται.
type: docs
weight: 92
url: /el/aspose.slides/backdrop3dscene/
---
## Backdrop3DScene κλάση

Ορίζει ένα επίπεδο στο οποίο εφαρμόζονται εφέ, όπως λάμψη και σκιά, σε σχέση με το σχήμα στο οποίο εφαρμόζονται.

```cpp
class Backdrop3DScene : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IBackdrop3DScene
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Συγκρίνει με το καθορισμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() override | Επιστρέφει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στον χώρο που αγκυροβολεί το επίπεδο υποβάθρου. Το 3D σημείο αναπαρίσταται από έναν πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση **float**[]. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() override | Επιστρέφει ένα διανύσμα κανονικό. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διανύσμα κανονικό προς την όψη του επιπέδου υποβάθρου. Το διανύσμα αναπαρίσταται από έναν πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση **float**[]. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει τον γονέα [IPresentationComponent](../ipresentationcomponent/). Μόνο για ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() override | Επιστρέφει ένα διανύσμα που αντιπροσωπεύει την κατεύθυνση πάνω. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διανύσμα που αντιπροσωπεύει την κατεύθυνση πάνω σε σχέση με την όψη του επιπέδου υποβάθρου. Το διανύσμα αναπαρίσταται από έναν πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Επιστρέφει κωδικό κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναγνωσης κατά την καθορισμένη τιμή. |
| void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Ορίζει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στον χώρο που αγκυροβολεί το επίπεδο υποβάθρου. Το 3D σημείο αναπαρίσταται από έναν πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Εγγραφή **float**[]. |
| void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Ορίζει ένα διανύσμα κανονικό. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διανύσμα κανονικό προς την όψη του επιπέδου υποβάθρου. Το διανύσμα αναπαρίσταται από έναν πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Εγγραφή **float**[]. |
| void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Ορίζει ένα διανύσμα που αντιπροσωπεύει την κατεύθυνση πάνω. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διανύσμα που αντιπροσωπεύει την κατεύθυνση πάνω σε σχέση με την όψη του επιπέδου υποβάθρου. Το διανύσμα αναπαρίσταται από έναν πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Εγγραφή **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα template ως αδύναμο δείκτη (αντί για shared). Επιτρέπει την εναλλαγή δεικτών σε containers σε weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής ανάγνωσης. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής ανάγνωσης. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [IBackdrop3DScene](../ibackdrop3dscene/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)