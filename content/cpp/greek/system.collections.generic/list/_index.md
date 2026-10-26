---
title: List
second_title: Αναφορά API του Aspose.Slides για C++
description: Προκαταρκτική δήλωση List.
type: docs
weight: 430
url: /el/system.collections.generic/list/
---
## List κλάση

[List](./) προεγκεκριμένη δήλωση.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος στοιχείου. |
## Μέθοδοι

| Method | Description |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Ειδικό για C++. |
| void [Add](./add/)(const T\&) override | Προσθέτει στοιχείο στο τέλος της λίστας. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Προσθέτει στοιχεία στη λίστα· χρησιμοποιείται κατά τη μετάφραση αρχικοποιητών. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Προσθέτει όλα τα στοιχεία από τη συλλογή (ή από την ίδια) στο τέλος της τρέχουσας λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Λαμβάνει αναφορά μόνο για ανάγνωση σε αυτή τη συλλογή. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Λαμβάνει επαναλήπτη στο πρώτο στοιχείο της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Λαμβάνει επαναλήπτη στο πρώτο στοιχείο της συλλογής με const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Αναζητά στοιχείο σε ταξινομημένη λίστα. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Αναζητά στοιχείο σε ταξινομημένη λίστα. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Αναζητά στοιχείο σε ταξινομημένη λίστα. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Λαμβάνει επαναλήπτη στο πρώτο const-προσδιορισμένο στοιχείο της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Λαμβάνει επαναλήπτη για ένα μη υπάρχον const-προσδιορισμένο στοιχείο πίσω από το τέλος της συλλογής. |
| void [Clear](./clear/)() override | Διαγράφει όλα τα στοιχεία. |
| **bool** [Contains](./contains/)(const T\&) const override | Ελέγχει αν το στοιχείο υπάρχει στη λίστα. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Δημιουργεί λίστα στοιχείων που έχουν μετατραπεί σε διαφορετικό τύπο. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Αντιγράφει στοιχεία λίστας σε υπάρχοντα στοιχεία πίνακα. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Αντιγράφει όλα τα στοιχεία σε υπάρχοντα στοιχεία πίνακα. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Αντιγράφει στοιχεία ξεκινώντας από το συγκεκριμένο δείκτη σε υπάρχοντα στοιχεία πίνακα. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Λαμβάνει αντίστροφο επαναλήπτη στο τελευταίο const-προσδιορισμένο στοιχείο της συλλογής (πρώτο σε αντίστροφη σειρά). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Λαμβάνει αντίστροφο επαναλήπτη για μη υπάρχον const-προσδιορισμένο στοιχείο πριν από την αρχή της συλλογής. |
| [vector_t](./vector_t/)\& [data](./data/)() | Λειτουργία πρόσβασης στη δομή δεδομένων βάσης. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Λειτουργία πρόσβασης στη δομή δεδομένων βάσης. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Λαμβάνει επαναλήπτη για ένα μη υπάρχον στοιχείο πίσω από το τέλος της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Λαμβάνει επαναλήπτη για ένα μη υπάρχον στοιχείο πίσω από το τέλος της συλλογής με const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσοι παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσοι παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Ελέγχει αν υπάρχει στοιχείο που ικανοποιεί συγκεκριμένο καθοριστικό στη λίστα. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο καθοριστικό. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχεία που ικανοποιούν συγκεκριμένο καθοριστικό. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο καθοριστικό. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο καθοριστικό. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί συγκεκριμένο καθοριστικό. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά το τελευταίο στοιχείο που ικανοποιεί συγκεκριμένο καθοριστικό. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Εφαρμόζει ενέργεια σε όλα τα στοιχεία της λίστας. |
| int [get_Capacity](./get_capacity/)() const | Λαμβάνει την τρέχουσα χωρητικότητα της λίστας. |
| int [get_Count](./get_count/)() const override | Λαμβάνει τον αριθμό των στοιχείων στην τρέχουσα λίστα. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Ελέγχει αν η συλλογή είναι σταθερού μεγέθους. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ελέγχει αν η συλλογή είναι μόνο για ανάγνωση. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Λαμβάνει το αντικείμενο μέσω του οποίου συγχρονίζεται η συλλογή. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Λαμβάνει επαναλήπτη για να διασχίσει τα στοιχεία της λίστας. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμένη των προσαρμοσμένων αντικειμένων. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Creates slice of list. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Κατασκευαστής προεπιλογής. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Κατασκευαστής αντιγραφής. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Κατασκευαστής μετακίνησης. |
| T [idx_get](./idx_get/)(int) const override | Λαμβάνει στοιχείο σε συγκεκριμένη θέση. |
| void [idx_set](./idx_set/)(int, T) override | Θέτει στοιχείο σε συγκεκριμένη θέση. |
| int [IndexOf](./indexof/)(const T\&) const override | Λαμβάνει τον πρώτο δείκτη συγκεκριμένου στοιχείου. |
| int [IndexOf](./indexof/)(const T\&, int) const | Αναζητά συγκεκριμένο στοιχείο στη λίστα. |
| void [Insert](./insert/)(int, const T\&) override | Εισάγει στοιχείο στην καθορισμένη θέση. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Εισάγει εύρος δεδομένων σε συγκεκριμένη θέση. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Αναζητά το συγκεκριμένο αντικείμενο και επιστρέφει το μηδενικό-βασισμένο δείκτη της τελευταίας εμφάνισης στο σύνολο της λίστας. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Αναζητά το συγκεκριμένο αντικείμενο και επιστρέφει το μηδενικό-βασισμένο δείκτη της τελευταίας εμφάνισης στο εύρος των στοιχείων στο [List](./) που εκτείνεται από το πρώτο στοιχείο έως τον καθορισμένο δείκτη. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Αναζητά το συγκεκριμένο αντικείμενο και επιστρέφει το μηδενικό-βασισμένο δείκτη της τελευταίας εμφάνισης στο εύρος των στοιχείων στο [List](./) που περιέχει τον καθορισμένο αριθμό στοιχείων και λήγει στον καθορισμένο δείκτη. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει μια συνάρτηση συγκεντρωτή πάνω σε μια ακολουθία. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει αν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Καθορίζει αν μια ακολουθία περιέχει οποιαδήποτε στοιχεία. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει αν υπάρχει οποιοδήποτε στοιχείο σε μια ακολουθία ή αν ικανοποιεί μια συνθήκη. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Κάνει cast τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Συνενώνει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Καθορίζει αν μια ακολουθία περιέχει μια συγκεκριμένη τιμή. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενο μέσω άμεσης καταμέτρησης). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν τη συγκεκριμένη συνθήκη. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_First](../ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί τη συγκεκριμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας, ή τιμή προεπιλογής εάν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή τιμή προεπιλογής αν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας, ή τιμή προεπιλογής εάν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη ελάχιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αυξανόμενη σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Αναστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Μετασχηματίζει στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν καθορισμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου predicat. |
|  [List](./list/)() | Δημιουργεί κενή λίστα. |
|  [List](./list/)(int) | Δημιουργεί λίστα με προ-καθορισμένη χωρητικότητα. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Κατασκευαστής αντιγραφής. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων για υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων για υποκλάσεις. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Τελεστής ανάθεσης κίνησης. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Τελεστής ανάθεσης κίνησης. |
| vector_t::reference [operator[]](./operator[]/)(int) | Συνάρτηση προσπέλασης. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Συνάρτηση προσπέλασης. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Λαμβάνει αντίστροφο επαναλήπτη στο τελευταίο στοιχείο της συλλογής (πρώτο σε αντίστροφη σειρά). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Λαμβάνει αντίστροφο επαναλήπτη στο τελευταίο στοιχείο της συλλογής με const (πρώτο σε αντίστροφη σειρά). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικειμένου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| **bool** [Remove](./remove/)(const T\&) override | Αφαιρεί την πρώτη εμφάνιση συγκεκριμένου στοιχείου από τη λίστα. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Αφαιρεί όλα τα στοιχεία που ταιριάζουν σε συγκεκριμένο predicat. |
| void [RemoveAt](./removeat/)(int) override | Αφαιρεί στοιχείο στην καθορισμένη θέση. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| void [RemoveRange](./removerange/)(int, int) | Αφαιρεί τμήμα της λίστας. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Λαμβάνει αντίστροφο επαναλήπτη για μη υπάρχον στοιχείο πριν από την αρχή της συλλογής. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Λαμβάνει αντίστροφο επαναλήπτη για μη υπάρχον στοιχείο πριν από την αρχή της συλλογής με const. |
| void [Reverse](./reverse/)() | Αντιστρέφει τη σειρά των στοιχείων ολόκληρης της λίστας. |
| void [Reverse](./reverse/)(int, int) | Αντιστρέφει τη σειρά των στοιχείων του τμήματος της λίστας. |
| void [set_Capacity](./set_capacity/)(int) | Ορίζει τη χωρητικότητα της λίστας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα του προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Ταξινομεί τα στοιχεία στη λίστα. |
| void [Sort](./sort/)() | Ταξινομεί τα στοιχεία στη λίστα χρησιμοποιώντας το προεπιλεγμένο σύγκριση. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Ταξινομεί τα στοιχεία στο τμήμα της λίστας. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ταξινομεί τα στοιχεία στη λίστα. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Μετατρέπει τη λίστα σε πίνακα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| void [TrimExcess](./trimexcess/)() | Κάνει τη χωρητικότητα της λίστας να ταιριάζει στο μέγεθός της. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Καθορίζει αν κάθε στοιχείο στη συλλογή ταιριάζει με τις συνθήκες που ορίζονται από το καθορισμένο predicat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Λαμβάνει την υλοποίηση του const επαναλήπτη begin για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Λαμβάνει την υλοποίηση του επαναλήπτη begin για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Λαμβάνει την υλοποίηση του const επαναλήπτη end για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Λαμβάνει την υλοποίηση του επαναλήπτη end για το τρέχον container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Τύποι ορισμού

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | Αυτός ο τύπος. |
| [BaseType](./basetype/) | Τύπος διεπαφής. |
| [vector_t](./vector_t/) | Βασικός τύπος δεδομένων. |
| [iterator](./iterator/) | Τύπος επαναλήπτη. |
| [const_iterator](./const_iterator/) | Τύπος σταθερού επαναλήπτη. |
| [reverse_iterator](./reverse_iterator/) | Τύπος αντίστροφου επαναλήπτη. |
| [const_reverse_iterator](./const_reverse_iterator/) | Τύπος σταθερού αντίστροφου επαναλήπτη. |
| [IEnumerablePtr](./ienumerableptr/) | Κοντέινερ που περιέχει στοιχεία του ίδιου τύπου που κρατάμε. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** τύπος. |
## Παρατηρήσεις

[List](./) - περιτύλιγμα γύρω από std::vector για χρήση σε μεταγλωτισμένο κώδικα. Απαιτεί την υλοποίηση του operator == για τον τύπο του στοιχείου. Αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο μέσω της συνάρτησης [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στο stack ή χρησιμοποιώντας operator new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assertion. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Δημιουργήστε την πρώτη λίστα.
  auto list1 = MakeObject<List<int>>();

  // Γεμίστε την πρώτη λίστα.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Ταξινομήστε την πρώτη λίστα.
  // Τα στοιχεία της πρώτης λίστας θα είναι: {-5, 1, 3, 8}
  list1->Sort();

  // Αφαιρέστε το στοιχείο στη θέση 2.
  // Τα στοιχεία της πρώτης λίστας θα είναι: {-5, 1, 8}
  list1->RemoveAt(2);

  // Εισάγετε το στοιχείο στη θέση 1.
  // Τα στοιχεία της πρώτης λίστας θα είναι: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Δημιουργήστε τη δεύτερη λίστα.
  auto list2 = MakeObject<List<int>>();

  // Γεμίστε τη δεύτερη λίστα.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Προσθέστε στοιχεία από τη δεύτερη λίστα στην πρώτη.
  list1->AddRange(list2);

  // Εκτυπώστε τα στοιχεία της πρώτης λίστας.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την παρακάτω έξοδο:
- 5 15 1 8 10 20 30
*/
```

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Κλάση [IList](../ilist/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)