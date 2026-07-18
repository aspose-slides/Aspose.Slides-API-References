---
title: ListExt
second_title: Αναφορά API Aspose.Slides για C++
description: γενική κλάση List που υλοποιεί τη διεπαφή IListWrapper
type: docs
weight: 443
url: /el/system.collections.generic/listext/
---
## ListExt κλάση

γενική [List](../list/) κλάση που υλοποιεί [IListWrapper](../../system.collections/ilistwrapper/) διεπαφή

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | Συγκεκριμένο για C++. |
| void [Add](../list/add/)(const T\&) override | Προσθέτει στοιχείο στο τέλος της λίστας. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Προσθέτει στοιχεία στη λίστα· χρησιμοποιείται όταν μεταφράζονται αρχικοποιητές. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Προσθέτει όλα τα στοιχεία από τη συλλογή (ή τον εαυτό της) στο τέλος της τρέχουσας λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Λαμβάνει αναφορά μόνο για ανάγνωση σε αυτή τη συλλογή. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Λαμβάνει επαναλήπτη στο πρώτο στοιχείο της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Λαμβάνει επαναλήπτη στο πρώτο στοιχείο της συλλογής με χαρακτηριστικό const. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Αναζητά το στοιχείο σε μια ταξινομημένη λίστα. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Αναζητά το στοιχείο σε μια ταξινομημένη λίστα. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Αναζητά το στοιχείο σε μια ταξινομημένη λίστα. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Λαμβάνει επαναλήπτη στο πρώτο στοιχείο με χαρακτηριστικό const της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Λαμβάνει επαναλήπτη για ένα μη υπάρχον στοιχείο με χαρακτηριστικό const πίσω από το τέλος της συλλογής. |
| void [Clear](../list/clear/)() override | Διαγράφει όλα τα στοιχεία. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Ελέγχει αν το στοιχείο υπάρχει στη λίστα. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Δημιουργεί μια λίστα στοιχείων μετατρεπμένων σε διαφορετικό τύπο. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Αντιγράφει τα στοιχεία της λίστας σε υπάρχοντα στοιχεία πίνακα. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Αντιγράφει όλα τα στοιχεία σε υπάρχοντα στοιχεία πίνακα. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Αντιγράφει στοιχεία ξεκινώντας από το καθορισμένο δείκτη σε υπάρχοντα στοιχεία πίνακα. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Λαμβάνει αντίστροφο επαναλήπτη στο τελευταίο στοιχείο με χαρακτηριστικό const της συλλογής (πρώτο σε αντίστροφη σειρά). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) υλοποίηση διεπαφής. |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) βοηθητικό υλοποίησης για τύπους αναφοράς. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) βοηθητικό υλοποίησης για τύπους τιμής. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) βοηθητικό υλοποίησης για άλλους τύπους. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Λαμβάνει αντίστροφο επαναλήπτη για ένα μη υπάρχον στοιχείο με χαρακτηριστικό const πριν από την αρχή της συλλογής. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Συνάρτηση πρόσβασης στη δομή δεδομένων υποβάθρου. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Συνάρτηση πρόσβασης στη δομή δεδομένων υποβάθρου. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Λαμβάνει επαναλήπτη για ένα μη υπάρχον στοιχείο πίσω από το τέλος της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Λαμβάνει επαναλήπτη για ένα μη υπάρχον στοιχείο πίσω από το τέλος της συγκεντρωμένης συλλογής με χαρακτηριστικό const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Ελέγχει αν υπάρχει στοιχείο που ικανοποιεί ένα συγκεκριμένο πρότυπο στη λίστα. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί ένα συγκεκριμένο πρότυπο. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχεία που ικανοποιούν ένα συγκεκριμένο πρότυπο. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί ένα συγκεκριμένο πρότυπο. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί ένα συγκεκριμένο πρότυπο. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Αναζητά στοιχείο που ικανοποιεί ένα συγκεκριμένο πρότυπο. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Αναζητά το τελευταίο στοιχείο που ικανοποιεί ένα συγκεκριμένο πρότυπο. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Εφαρμόζει ενέργεια σε όλα τα στοιχεία της λίστας. |
| int [get_Capacity](../list/get_capacity/)() const | Λαμβάνει την τρέχουσα χωρητικότητα της λίστας. |
| int [get_Count](../list/get_count/)() const override | Λαμβάνει τον αριθμό των στοιχείων στην τρέχουσα λίστα. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Ελέγχει εάν η συλλογή έχει σταθερό μέγεθος. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ελέγχει αν η συλλογή είναι μόνο για ανάγνωση. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Λαμβάνει το αντικείμενο μέσω του οποίου συγχρονίζεται η συλλογή. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Λαμβάνει enumerator για επανάληψη στα στοιχεία της λίστας. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Διευκολύνει το hashing προσαρμοσμένων αντικειμένων. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Δημιουργεί κομμάτι (slice) της λίστας. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Κατασκευαστής προεπιλογής. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Κατασκευαστής αντιγραφής. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Κατασκευαστής μετακίνησης. |
| T [idx_get](../list/idx_get/)(int) const override | Λαμβάνει το στοιχείο σε συγκεκριμένη θέση. |
| void [idx_set](../list/idx_set/)(int, T) override | Ορίζει το στοιχείο σε συγκεκριμένη θέση. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Λαμβάνει τον πρώτο δείκτη του συγκεκριμένου στοιχείου. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Αναζητά συγκεκριμένο στοιχείο στη λίστα. |
| void [Insert](../list/insert/)(int, const T\&) override | Εισάγει στοιχείο στην καθορισμένη θέση. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Εισάγει εύρος δεδομένων σε συγκεκριμένη θέση. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Αναζητά το καθορισμένο αντικείμενο και επιστρέφει τον μηδενικό-βασισμένο δείκτη της τελευταίας εμφάνισης στο σύνολο της λίστας. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Αναζητά το καθορισμένο αντικείμενο και επιστρέφει τον μηδενικό-βασισμένο δείκτη της τελευταίας εμφάνισης στο εύρος των στοιχείων στο [List](../list/) που εκτείνεται από το πρώτο στοιχείο έως τον καθορισμένο δείκτη. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Αναζητά το καθορισμένο αντικείμενο και επιστρέφει τον μηδενικό-βασισμένο δείκτη της τελευταίας εμφάνισης στο εύρος των στοιχείων στο [List](../list/) που περιέχει τον καθορισμένο αριθμό στοιχείων και τελειώνει στον καθορισμένο δείκτη. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει λειτουργία συσσωρευτή πάνω σε μια ακολουθία. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει εάν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Καθορίζει εάν μια ακολουθία περιέχει στοιχεία. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει εάν υπάρχει ή ικανοποιείται κάποια συνθήκη από οποιοδήποτε στοιχείο της ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Συνεχύει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Καθορίζει εάν μια ακολουθία περιέχει μια συγκεκριμένη τιμή. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογισμένο μέσω άμεσης μέτρησης). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν τη συγκεκριμένη συνθήκη. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε συγκεκριμένο δείκτη σε μια ακολουθία. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε συγκεκριμένο δείκτη σε μια ακολουθία. |
| T [LINQ_First](../ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί τη συγκεκριμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή εάν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη τιμή που προκύπτει. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη ελάχιστη τιμή που προκύπτει. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν καθορισμένο αριθμό διαδοχικών στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Δημιουργεί πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Δημιουργεί List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου πρότυπου. |
|  [List](../list/list/)() | Δημιουργεί κενή λίστα. |
|  [List](../list/list/)(int) | Δημιουργεί λίστα με προ-ορισμένη χωρητικότητα. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Κατασκευαστής αντιγραφής. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση κλειδώματος C# lock() . Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Διευκολύνει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Τελεστής ανάθεσης μετακίνησης. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Συνάρτηση προσπέλασης. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Συνάρτηση προσπέλασης. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Λαμβάνει αντίστροφο επαναλήπτη στο τελευταίο στοιχείο της συλλογής (πρώτο σε αντίστροφη σειρά). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Λαμβάνει αντίστροφο επαναλήπτη στο τελευταίο στοιχείο της συλλογής με χαρακτηριστικό const (πρώτο σε αντίστροφη σειρά). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση strings. |
| **bool** [Remove](../list/remove/)(const T\&) override | Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου στοιχείου από τη λίστα. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Αφαιρεί όλα τα στοιχεία που ταιριάζουν σε συγκεκριμένο πρότυπο. |
| void [RemoveAt](../list/removeat/)(int) override | Αφαιρεί στοιχείο στη συγκεκριμένη θέση. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [RemoveRange](../list/removerange/)(int, int) | Αφαιρεί κομμάτι (slice) λίστας. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Λαμβάνει αντίστροφο επαναλήπτη για ένα μη υπάρχον στοιχείο πριν από την αρχή της συλλογής. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Λαμβάνει αντίστροφο επαναλήπτη για ένα μη υπάρχον στοιχείο πριν από την αρχή της συγκεντρωμένης συλλογής με χαρακτηριστικό const. |
| void [Reverse](../list/reverse/)() | Αντιστρέφει τη σειρά των στοιχείων ολόκληρης της λίστας. |
| void [Reverse](../list/reverse/)(int, int) | Αντιστρέφει τη σειρά των στοιχείων του τμήματος λίστας. |
| void [set_Capacity](../list/set_capacity/)(int) | Ορίζει τη χωρητικότητα της λίστας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Θέτει το n-οστό όρισμα προτύπου σε αδυναμία pointer (αντί για shared). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδυναμία λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Ταξινομεί τα στοιχεία στη λίστα. |
| void [Sort](../list/sort/)() | Ταξινομεί τα στοιχεία στη λίστα χρησιμοποιώντας τον προεπιλεγμένο συγκριτή. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Ταξινομεί τα στοιχεία στο τμήμα λίστας. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ταξινομεί τα στοιχεία στη λίστα. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Μετατρέπει τη λίστα σε πίνακα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Διευκολύνει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| void [TrimExcess](../list/trimexcess/)() | Ρυθμίζει τη χωρητικότητα της λίστας ώστε να ταιριάζει με το μέγεθός της. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Καθορίζει εάν όλα τα στοιχεία της συλλογής ταιριάζουν με τις συνθήκες του συγκεκριμένου πρότυπου. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Λαμβάνει την υλοποίηση του const αρχικού επαναλήπτη για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Λαμβάνει την υλοποίηση του αρχικού επαναλήπτη για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Λαμβάνει την υλοποίηση του const τελικού επαναλήπτη για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Λαμβάνει την υλοποίηση του τελικού επαναλήπτη για το τρέχον container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδυναμίας αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδυναμίας αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα pointers ή ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Typedef | Περιγραφή |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## Δείτε επίσης

* Κλάση [List](../list/)
* Κλάση [IListWrapper](../../system.collections/ilistwrapper/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)