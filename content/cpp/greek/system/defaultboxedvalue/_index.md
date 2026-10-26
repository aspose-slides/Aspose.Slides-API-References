---
title: DefaultBoxedValue
second_title: Aspose.Slides για C++ API Αναφορά
description: "Υλοποίηση κλάσης BoxedValue. Επιτρέπει στις ειδικεύσεις BoxingValue να δηλώνονται χωρίς την αντιγραφή του κοινό κώδικα. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 274
url: /el/system/defaultboxedvalue/
---
## DefaultBoxedValue κλάση


[BoxedValue](../boxedvalue/) υλοποίηση κλάσης. Επιτρέπει στις εξειδικεύσεις BoxingValue να δηλώνονται χωρίς την αντιγραφή κοινού κώδικα. Τα αντικείμενα αυτής της κλάσης πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργήσετε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Δημιουργεί ένα νέο αντικείμενο της κλάσης [DefaultBoxedValue](./) που αντιπροσωπεύει την καθορισμένη τιμή. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Καθορίζει την ισότητα των στοιβαγμένων τιμών που αντιπροσωπεύονται από το τρέχον και το καθορισμένο αντικείμενο. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Προσομοίζει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| int [GetHashCode](./gethashcode/)() const override | Επιστρέφει έναν κωδικό κατακερμώματος για το τρέχον αντικείμενο. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Αποκτά τον πραγματικό τύπο του αντικειμένου. |
| **bool** [is](./is/)() const | Καθορίζει εάν ο τύπος της στοιβαγμένης τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι **V**. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή 'is' της C#. |
| void [Lock](../object/lock/)() | Εφαρμόζει το κλείδωμα της εντολής lock() της C#. Κλήση απευθείας ή χρήση του αντικειμένου πύλης [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου [Object.MemberwiseClone()](../object/memberwiseclone/) της C#. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς ξεκινά νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών υποκλάσεων. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς ξεκινά νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών υποκλάσεων. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινή). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδυνατό (weak) τρόπο. |
| int [SharedCount](../object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να κλήνεται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να κλήνεται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Επιστρέφει την αλφαριθμητική αναπαράσταση της στοιβαγμένης τιμής. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί την κατασκευή typeof([System.Object](../object/)) της C#. |
| const T\& [unbox](./unbox/)() const | Απο-συσκευάζει (unbox) τη στοιβαγμένη τιμή. |
| void [Unlock](../object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής lock() της C#. Κλήση απευθείας ή χρήση του αντικειμένου πύλης [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κλήνεται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κλήνεται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../object/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)