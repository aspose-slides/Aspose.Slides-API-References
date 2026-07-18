---
title: X509Certificate2Collection
second_title: Αναφορά API του Aspose.Slides για C++
description: "Συλλογή αντικειμένων πιστοποιητικού X509. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject() . Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να τυλίγετε αυτή την κλάση σε δείκτη System::SmartPtr και να χρησιμοποιείτε αυτόν το δείκτη για να το περάσετε ως όρισμα σε συναρτήσεις."
type: docs
weight: 53
url: /el/system.security.cryptography.x509certificates/x509certificate2collection/
---
## X509Certificate2Collection κλάση

Συλλογή αντικειμένων πιστοποιητικού X509. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να τυλίγετε αυτή την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν το δείκτη για να το περάσετε ως όρισμα σε συναρτήσεις.

```cpp
class X509Certificate2Collection : public System::Collections::Generic::List<SharedPtr<X509Certificate2>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | Σχετικό με C++. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | Προσθέτει στοιχείο στο τέλος της λίστας. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | Προσθέτει στοιχεία στη λίστα· χρησιμοποιείται όταν μεταφράζονται αρχικοποιητές. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Προσθέτει όλα τα στοιχεία από τη συλλογή (ή από τον εαυτό της) στο τέλος της τρέχουσας λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | Λαμβάνει αναφορά μόνο για ανάγνωση σε αυτή τη συλλογή. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | Λαμβάνει iterator προς το πρώτο στοιχείο της συλλογής. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | Λαμβάνει iterator προς το πρώτο στοιχείο της συλλογής με const. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | Αναζητά το στοιχείο σε μια ταξινομημένη λίστα. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Αναζητά το στοιχείο σε μια ταξινομημένη λίστα. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Αναζητά το στοιχείο σε μια ταξινομημένη λίδα. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | Λαμβάνει iterator προς το πρώτο στοιχείο της συλλογής με const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | Λαμβάνει iterator για ένα μη υπάρχον στοιχείο με const πίσω από το τέλος της συλλογής. |
| void [Clear](../../system.collections.generic/list/clear/)() override | Διαγράφει όλα τα στοιχεία. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | Ελέγχει εάν το στοιχείο υπάρχει στη λίστα. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Δημιουργεί μια λίστα στοιχείων που μετατρέπονται σε διαφορετικό τύπο. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Αντιγράφει τα στοιχεία της λίστας σε υπάρχοντα στοιχεία πίνακα. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Αντιγράφει όλα τα στοιχεία σε υπάρχοντα στοιχεία πίνακα. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Αντιγράφει στοιχεία ξεκινώντας από το καθορισμένο δείκτη σε υπάρχοντα στοιχεία πίνακα. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | Λαμβάνει reverse iterator προς το τελευταίο στοιχείο της συλλογής με const (πρώτο σε ανάποδη σειρά). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | Λαμβάνει reverse iterator για ένα μη υπάρχον στοιχείο με const πριν από την αρχή της συλλογής. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | Λειτουργία πρόσβασης στην υποκείμενη δομή δεδομένων. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | Λειτουργία πρόσβασης στην υποκείμενη δομή δεδομένων. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | Λαμβάνει iterator για ένα μη υπάρχον στοιχείο πίσω από το τέλος της συλλογής. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | Λαμβάνει iterator για ένα μη υπάρχον στοιχείο πίσω από το τέλος της συλλογής με const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Ελέγχει εάν υπάρχει στοιχείο που ικανοποιεί συγκεκριμένο πρότυπο στη λίστα. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο πρότυπο. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχεία που ικανοποιούν συγκεκριμένο πρότυπο. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο πρότυπο. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο πρότυπο. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο πρότυπο. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά το τελευταίο στοιχείο που ικανοποιεί συγκεκριμένο πρότυπο. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | Εφαρμόζει δράση σε όλα τα στοιχεία της λίστας. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | Λαμβάνει την τρέχουσα χωρητικότητα της λίστας. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | Λαμβάνει τον αριθμό των στοιχείων στην τρέχουσα λίστα. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Ελέγχει εάν η συλλογή είναι σταθερού μεγέθους. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Ελέγχει εάν η συλλογή είναι μόνο για ανάγνωση. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Λαμβάνει το αντικείμενο μέσω του οποίου συγχρονίζεται η συλλογή. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | Λαμβάνει enumerator για διάσχιση των στοιχείων της λίστας. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | Δημιουργεί κομμάτι (slice) της λίστας. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογο κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Προεπιλεγμένος κατασκευαστής. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Κατασκευαστής αντιγραφής. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Κατασκευαστής μετακίνησης. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | Λαμβάνει στοιχείο σε συγκεκριμένη θέση. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | Ορίζει στοιχείο σε συγκεκριμένη θέση. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | Λαμβάνει τον πρώτο δείκτη του συγκεκριμένου στοιχείου. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | Αναζητά συγκεκριμένο στοιχείο στη λίστα. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | Εισάγει στοιχείο στη συγκεκριμένη θέση. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Εισάγει εύρος δεδομένων σε συγκεκριμένη θέση. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου όπως περιγράφεται από targetType. Αναλογο του τελεστή C# 'is'. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | Αναζητά το συγκεκριμένο αντικείμενο και επιστρέφει τον δείκτη που ξεκινά από το μηδέν της τελευταίας εμφάνισης μέσα σε ολόκληρη τη λίστα. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | Αναζητά το συγκεκριμένο αντικείμενο και επιστρέφει τον μηδενικό δείκτη της τελευταίας εμφάνισης εντός του εύρους στοιχείων στο [List](../../system.collections.generic/list/) που εκτείνεται από το πρώτο στοιχείο έως τον καθορισμένο δείκτη. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Αναζητά το συγκεκριμένο αντικείμενο και επιστρέφει τον μηδενικό δείκτη της τελευταίας εμφάνισης εντός του εύρους στοιχείων στο [List](../../system.collections.generic/list/) που περιέχει τον καθορισμένο αριθμό στοιχείων και τελειώνει στον καθορισμένο δείκτη. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει συνάρτηση συσσωρευτή πάνω σε μια ακολουθία. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει εάν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Καθορίζει εάν μια ακολουθία περιέχει στοιχεία. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει εάν υπάρχει κάποιο στοιχείο σε μια ακολουθία ή αν ικανοποιεί μια συνθήκη. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Συνενώνει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Καθορίζει εάν μια ακολουθία περιέχει μια συγκεκριμένη τιμή. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενο μέσω άμεσης καταμέτρησης). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν την καθορισμένη συνθήκη. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί την καθορισμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας, ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή αν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας, ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μικρότερη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Φίλτρου τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Αντιστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Μετασχηματίζει τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε μια νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν καθορισμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φίλτρου μια ακολουθία βάσει του καθορισμένου προτύπου. |
|  [List](../../system.collections.generic/list/list/)() | Δημιουργεί κενή λίστα. |
|  [List](../../system.collections.generic/list/list/)(int) | Δημιουργεί λίστα με προκαθορισμένη χωρητικότητα. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Κατασκευαστής αντιγραφής. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκλάσεων. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Τελεστής ανάθεσης μετακίνησης. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | Συνάρτηση πρόσβασης. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | Συνάρτηση πρόσβασης. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | Λαμβάνει reverse iterator προς το τελευταίο στοιχείο της συλλογής (πρώτο σε ανάποδη σειρά). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | Λαμβάνει reverse iterator προς το τελευταίο στοιχείο της συλλογής με const (πρώτο σε ανάποδη σειρά). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικευμένη υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | Αφαιρεί την πρώτη παρουσία συγκεκριμένου στοιχείου από τη λίστα. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Αφαιρεί όλα τα στοιχεία που ταιριάζουν με το συγκεκριμένο πρότυπο. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | Αφαιρεί το στοιχείο στη καθορισμένη θέση. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | Αφαιρεί κομμάτι (slice) της λίστας. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | Λαμβάνει reverse iterator για ένα μη υπάρχον στοιχείο πριν από την αρχή της συλλογής. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | Λαμβάνει reverse iterator για ένα μη υπάρχον στοιχείο πριν από την αρχή της συλλογής με const. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | Αντιστρέφει τη σειρά των στοιχείων ολόκληρης της λίστας. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | Αντιστρέφει τη σειρά των στοιχείων του κομματιού λίστας. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | Ορίζει τη χωρητικότητα της λίστας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως weak pointer (αντί για shared). Επιτρέπει την αλλαγή δεικτών σε containers σε weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Ταξινομεί τα στοιχεία στη λίστα. |
| void [Sort](../../system.collections.generic/list/sort/)() | Ταξινομεί τα στοιχεία στη λίστα χρησιμοποιώντας προεπιλεγμένο συγκριτή. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | Ταξινομεί τα στοιχεία στο κομμάτι της λίστας. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ταξινομεί τα στοιχεία στη λίστα. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | Μετατρέπει τη λίστα σε πίνακα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | Ρυθμίζει τη χωρητικότητα της λίστας ώστε να ταιριάζει με το μέγεθός της. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Καθορίζει εάν κάθε στοιχείο στη συλλογή ταιριάζει με τις συνθήκες που ορίζονται από το καθορισμένο πρότυπο. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | Λαμβάνει την υλοποίηση του const iterator begin για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | Λαμβάνει την υλοποίηση του iterator begin για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | Λαμβάνει την υλοποίηση του const iterator end για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | Λαμβάνει την υλοποίηση του iterator end για το τρέχον container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή weak αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή weak αναφορών. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [List](../../system.collections.generic/list/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)