---
title: ValueTask
second_title: Αναφορά API Aspose.Slides για C++
description: Παρέχει ένα αποτέλεσμα που μπορεί να περιμένει (awaitable) μιας ασύγχρονης λειτουργίας.
type: docs
weight: 92
url: /el/system.threading.tasks/valuetask/
---
## ValueTask κλάση

Provides an awaitable result of an asynchronous operation.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [TaskPtr](../../system/taskptr/) [AsTask](./astask/)() const | Μετατρέπει αυτό το [ValueTask](./) σε έναν κοινό δείκτη προς [Task](../task/). |
| [Runtime::CompilerServices::ConfiguredValueTaskAwaitable](../../system.runtime.compilerservices/configuredvaluetaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | Διαμορφώνει έναν awaiter για αυτήν την εργασία. |
| **bool** [Equals](./equals/)([ValueTask](./)) override | Καθορίζει εάν αυτή η παρουσία ισούται με άλλη παρουσία [ValueTask](./). |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Καθορίζει εάν αυτή η παρουσία ισούται με άλλο αντικείμενο. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Καθορίζει εάν τα τρέχοντα και τα καθορισμένα αντικείμενα είναι ίσα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν η εργασία ολοκληρώθηκε λόγω ακύρωσης. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν η εργασία έχει ολοκληρωθεί. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν η εργασία ολοκληρώθηκε επιτυχώς. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν η εργασία ολοκληρώθηκε λόγω μη επεξεργασμένου σφάλματος. |
| [Runtime::CompilerServices::ValueTaskAwaiter](../../system.runtime.compilerservices/valuetaskawaiter/) [GetAwaiter](./getawaiter/)() const | Λαμβάνει έναν awaiter για αυτήν την εργασία για να υποστηρίξει εκφράσεις await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
| **bool** [operator!=](./operator_not_equal/)(const [ValueTask](./)\&) const | Τελεστής ανισότητας για [ValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTask](./)\&) const | Τελεστής ισότητας για [ValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινό μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινό μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινό μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
|  [ValueTask](./valuetask/)() | Δημιουργεί ένα κενό, μη αρχικοποιημένο [ValueTask](./). |
|  [ValueTask](./valuetask/)(const [TaskPtr](../../system/taskptr/)\&) | Δημιουργεί ένα [ValueTask](./) από έναν κοινό δείκτη σε ένα [Task](../task/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IEquatable](../../system/iequatable/)
* Χώρος ονομάτων [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)