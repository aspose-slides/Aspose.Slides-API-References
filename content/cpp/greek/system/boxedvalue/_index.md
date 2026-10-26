---
title: BoxedValue
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αναπαριστά μια συσκευασμένη τιμή. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε εμφάνιση αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 105
url: /el/system/boxedvalue/
---
## BoxedValue κλάση


Αναπαριστά μια συσκευασμένη τιμή. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργείτε εμφάνιση αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος της συσκευασμένης τιμής που αναπαριστά η κλάση |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | Δημιουργεί ένα αντικείμενο που αναπαριστά την καθορισμένη τιμή σε συσκευασμένη μορφή. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Καθορίζει την ισότητα των συσκευασμένων τιμών που αναπαρίστανται από το τρέχον και το καθορισμένο αντικείμενο. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση floating point σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| int [GetHashCode](./gethashcode/)() const override | Επιστρέφει έναν κώδικα κατακερματισμού για το τρέχον αντικείμενο. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | Επιστρέφει την τιμή που αντιπροσωπεύει τον τύπο της συσκευασμένης τιμής που αναπαρίσταται από το τρέχον αντικείμενο. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Επιστρέφει την αριθμητική τιμή του συσκευασμένου αντικειμένου εάν μπορεί να μετατραπεί, διαφορετικά μηδέν. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| **bool** [is](./is/)() const | Καθορίζει εάν ο τύπος της συσκευασμένης τιμής που αναπαρίσταται από το τρέχον αντικείμενο είναι **V**. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Καθορίζει εάν το τρέχον αντικείμενο αντιπροσωπεύει μια συσκευασμένη τιμή τύπου enum. |
| void [Lock](../object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κληθεί άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφής υποκατηγοριών. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφής υποκατηγορίων. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Συσκευάζει την τιμή της σταθεράς απαρίθμησης της καθορισμένης απαρίθμησης με το καθορισμένο όνομα. Ένα όρισμα καθορίζει αν η διάκριση πεζών-κεφαλαίων πρέπει να αγνοηθεί κατά την ερμηνεία της συμβολοσειράς που υποδεικνύει το όνομα της σταθεράς απαρίθμησης. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Συσκευάζει την τιμή της σταθεράς απαρίθμησης της καθορισμένης απαρίθμησης με το καθορισμένο όνομα. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν' όρισμα προτύπου ως αδυναμικό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδυναμική λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Λαμβάνει τη τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Μετατρέπει τη συσκευασμένη τιμή που αναπαρίσταται από το τρέχον αντικείμενο σε συμβολοσειρά. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Μετατρέπει το συσκευασμένο αντικείμενο σε συμβολοσειρά χρησιμοποιώντας την καθορισμένη συμβολοσειρά μορφοποίησης. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | Αποσυσκευάζει τη τιμή που αναπαρίσταται από το τρέχον αντικείμενο. |
| void [Unlock](../object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κληθεί άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδυναμικό μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδυναμικό μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [BoxedValueBase](../boxedvaluebase/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)