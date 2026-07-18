---
title: ISet
second_title: Aspose.Slides για C++ API Αναφορά
description: "Διεπαφή συλλογής που περιέχει ένα σύνολο μοναδικών στοιχείων. Αντικείμενα αυτής της κλάσης πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 352
url: /el/system.collections.generic/iset/
---
## ISet κλάση

Διεπαφή συλλογής που περιέχει ένα σύνολο μοναδικών στοιχείων. Αντικείμενα αυτής της κλάσης πρέπει να κατασκευάζονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος στοιχείου. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [Add](../icollection/add/)(const T\&) | Προσθέτει στοιχείο στη συλλογή. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Λαμβάνει έναν iterator που δείχνει στο πρώτο στοιχείο (αν υπάρχει) της συλλογής. Αυτός ο iterator δεν μπορεί να χρησιμοποιηθεί για την αλλαγή του αναφερόμενου αντικειμένου επειδή το [GetEnumerator()](../ienumerable/getenumerator/) επιστρέφει ένα αντίγραφο του T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Λαμβάνει έναν iterator που δείχνει στο πρώτο στοιχείο (αν υπάρχει) της στιγμής της συλλογής με προσδιορισμό const. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Λαμβάνει έναν iterator που δείχνει στο πρώτο στοιχείο με προσδιορισμό const (αν υπάρχει) της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Λαμβάνει έναν iterator που δείχνει ακριβώς μετά το τελευταίο στοιχείο με προσδιορισμό const (αν υπάρχει) της συλλογής. |
| virtual void [Clear](../icollection/clear/)() | Διαγράφει όλα τα στοιχεία από τη συλλογή. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Ελέγχει αν το στοιχείο υπάρχει στη συλλογή. |
| virtual void [CopyTo](../icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Αντιγράφει όλα τα στοιχεία της συλλογής σε υπάρχοντα στοιχεία πίνακα. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Λαμβάνει έναν iterator που δείχνει ακριβώς μετά το τελευταίο στοιχείο (αν υπάρχει) της συλλογής. Αυτός ο iterator δεν μπορεί να χρησιμοποιηθεί για την αλλαγή του αναφερόμενου αντικειμένου επειδή το [GetEnumerator()](../ienumerable/getenumerator/) επιστρέφει ένα αντίγραφο του T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Λαμβάνει έναν iterator που δείχνει ακριβώς μετά το τελευταίο στοιχείο (αν υπάρχει) της στιγμής της συλλογής με προσδιορισμό const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση δεκαδικής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual void [ExceptWith](./exceptwith/)([IEnumerablePtr](./ienumerableptr/)) | Αφαιρεί μια ομάδα στοιχείων. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual int [get_Count](../icollection/get_count/)() const | Λαμβάνει τον αριθμό των στοιχείων στη συλλογή. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ελέγχει αν η συλλογή είναι μόνο για ανάγνωση. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Λαμβάνει το αντικείμενο μέσω του οποίου συγχρονίζεται η συλλογή. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | Λαμβάνει enumerator. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](../icollection/icollection/)() | Κατασκευαστής προεπιλογής. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Κατασκευαστής αντιγραφής. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Κατασκευαστής μετακίνησης. |
| virtual void [IntersectWith](./intersectwith/)([IEnumerablePtr](./ienumerableptr/)) | Αφαιρεί στοιχεία που δεν υπάρχουν σε διαφορετικό κοντέινερ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| virtual **bool** [IsProperSubsetOf](./ispropersubsetof/)([IEnumerablePtr](./ienumerableptr/)) | Ελέγχει αν το τρέχον σύνολο είναι αυστηρό υποσύνολο του άλλου κοντέινερ. |
| virtual **bool** [IsProperSupersetOf](./ispropersupersetof/)([IEnumerablePtr](./ienumerableptr/)) | Ελέγχει αν το τρέχον σύνολο είναι αυστηρό υπερσύνολο του άλλου κοντέινερ. |
| virtual **bool** [IsSubsetOf](./issubsetof/)([IEnumerablePtr](./ienumerableptr/)) | Ελέγχει αν το τρέχον σύνολο είναι υποσύνολο του άλλου κοντέινερ. |
| virtual **bool** [IsSupersetOf](./issupersetof/)([IEnumerablePtr](./ienumerableptr/)) | Ελέγχει αν το τρέχον σύνολο είναι υπερσύνολο του άλλου κοντέινερ. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει μια συνάρτηση συγκεντρωτή σε μια ακολουθία. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει αν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Καθορίζει αν μια ακολουθία περιέχει οποιαδήποτε στοιχεία. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει αν υπάρχει οποιοδήποτε στοιχείο σε μια ακολουθία ή αν ικανοποιεί μια συνθήκη. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Συνενώνει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Καθορίζει αν μια ακολουθία περιέχει μια συγκεκριμένη τιμή. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογισμένο μέσω άμεσης καταμέτρησης). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν τη συγκεκριμένη συνθήκη. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε ένα καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε ένα καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_First](../ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί τη συγκεκριμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή αν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μικρότερη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Αντιστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Μετασχηματίζει τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν καθορισμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου λογικού όρου. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλαδιών μέσω αντιγραφής. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Τελεστής ανάθεσης μετακίνησης. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλαδιών μέσω αντιγραφής. |
| virtual **bool** [Overlaps](./overlaps/)([IEnumerablePtr](./ienumerableptr/)) | Ελέγχει αν το σύνολο επικαλύπτεται με άλλον κοντέινερ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Διαγράφει στοιχείο από τη συλλογή. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual **bool** [SetEquals](./setequals/)([IEnumerablePtr](./ienumerableptr/)) | Ελέγχει αν το σύνολο και ο κοντέινερ περιέχουν τα ίδια στοιχεία. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε κοντέινερ σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή το ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή το ThisProtector. |
| virtual void [SymmetricExceptWith](./symmetricexceptwith/)([IEnumerablePtr](./ienumerableptr/)) | Υπολογίζει τη συμμετρική εξαίρεση δύο κοντέινερ. Αφαιρεί όλα τα στοιχεία που είναι παρόντα και στα δύο κοντέινερ, ενώ ταυτόχρονα προσθέτει όλα τα στοιχεία που είναι παρόντα στο **other**, αλλά όχι στο τρέχον σύνολο. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| virtual void [UnionWith](./unionwith/)([IEnumerablePtr](./ienumerableptr/)) | Προσθέτει στοιχεία από την καθορισμένη συλλογή που δεν υπάρχουν ακόμη στο τρέχον σύνολο. |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Λαμβάνει την υλοποίηση του begin const iterator για τον τρέχοντα κοντέινερ. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Λαμβάνει την υλοποίηση του begin iterator για τον τρέχοντα κοντέινερ. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Λαμβάνει την υλοποίηση του end const iterator για τον τρέχοντα κοντέινερ. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Λαμβάνει την υλοποίηση του end iterator για τον τρέχοντα κοντέινερ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή το ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή το ThisProtector. |
| virtual [~ICollection](../icollection/~icollection/)() | Καταστροφέας. |
| virtual [~ISet](./~iset/)() | Καταστροφέας. |
| virtual [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Μετατοποποιήσεις

| Μετορισμός | Περιγραφή |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Τύπος που μπορεί να χρησιμοποιηθεί για τη σύγκριση των περιεχομένων του τρέχοντος συνόλου. |

## Δείτε επίσης

* Κλάση [ICollection](../icollection/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)