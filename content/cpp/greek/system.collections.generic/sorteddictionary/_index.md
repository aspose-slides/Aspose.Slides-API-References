---
title: SortedDictionary
second_title: Aspose.Slides για C++ Αναφορά API
description: Δήλωση προ-δηλωτικού τύπου ταξινομημένου λεξικού.
type: docs
weight: 521
url: /el/system.collections.generic/sorteddictionary/
---
## SortedDictionary κλάση

Sorted dictionary type forward declaration.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Τύπος κλειδιού. |
| TValue | Τύπος τιμής. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | Προσθέτει ζεύγος κλειδιού-τιμής στο container. |
| virtual void [Add](../icollection/add/)(const T&) | Προσθέτει στοιχείο στη συλλογή. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Λαμβάνει iterator που δείχνει στο πρώτο στοιχείο (εφόσον υπάρχει) της συλλογής. Αυτός ο iterator δεν μπορεί να χρησιμοποιηθεί για να αλλάξει το αναφερόμενο αντικείμενο επειδή το [GetEnumerator()](../ienumerable/getenumerator/) επιστρέφει ένα αντικείμενο-αντίγραφο του T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Λαμβάνει iterator που δείχνει στο πρώτο στοιχείο (εφόσον υπάρχει) της const-προσδιορισμένης παρουσίας της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Λαμβάνει iterator που δείχνει στο πρώτο const-προσδιορισμένο στοιχείο (εφόσον υπάρχει) της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Λαμβάνει iterator που δείχνει αμέσως μετά το τελευταίο const-προσδιορισμένο στοιχείο (εφόσον υπάρχει) της συλλογής. |
| virtual void [Clear](../icollection/clear/)() | Διαγράφει όλα τα στοιχεία από τη συλλογή. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | Ελέγχει αν το στοιχείο υπάρχει στη συλλογή. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | Ελέγχει αν το container περιέχει το κλειδί. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | Αντιγράφει τα περιεχόμενα του λεξικού σε υπάρχοντα στοιχεία του πίνακα. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Λαμβάνει reverse iterator προς το τελευταίο const-προσδιορισμένο στοιχείο της συλλογής (πρώτο στο αντίστροφο). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Λαμβάνει reverse iterator για ένα μη-υπάρχον const-προσδιορισμένο στοιχείο πριν από την αρχή της συλλογής. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Λαμβάνει iterator που δείχνει αμέσως μετά το τελευταίο στοιχείο (εφόσον υπάρχει) της συλλογής. Αυτός ο iterator δεν μπορεί να χρησιμοποιηθεί για να αλλάξει το αναφερόμενο αντικείμενο επειδή το [GetEnumerator()](../ienumerable/getenumerator/) επιστρέφει ένα αντικείμενο-αντίγραφο του T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Λαμβάνει iterator που δείχνει αμέσως μετά το τελευταίο στοιχείο (εφόσον υπάρχει) της const-προσδιορισμένης παρουσίας της συλλογής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Εξακολουθεί σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Εξακολουθεί σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Μόνο για εσωτερική χρήση. |
| [SharedPtr](../../system/sharedptr/)<[System::Collections::Generic::IComparer](../icomparer/)<TKey>> [get_Comparer](./get_comparer/)() const | Λαμβάνει το IComparer<TKey> που χρησιμοποιείται για την ταξινόμηση των στοιχείων του SortedDictionary<TKey,TValue>. |
| virtual int [get_Count](../icollection/get_count/)() const | Λαμβάνει τον αριθμό των στοιχείων στη συλλογή. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Ελέγχει αν το μέγεθος της συλλογής είναι σταθερό. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ελέγχει αν η συλλογή είναι μόνο για ανάγνωση. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Ελέγχει αν το container είναι ασφαλές ως προς νήματα. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](../idictionary/get_keys/)() const | Προσπελαίνει τη συλλογή κλειδιών. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | Λαμβάνει το αντικείμενο μέσω του οποίου συγχρονίζεται η συλλογή. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](../idictionary/get_values/)() const | Προσπελαίνει τη συλλογή τιμών. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| static [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Λειτουργία πρόσβασης singleton. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Λαμβάνει enumerator για επανάληψη στο τρέχον λεξικό. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | Επιστρέφει την τιμή αν βρεθεί· ή **Value()** αλλιώς. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Επιστρέφει την τιμή αν βρεθεί· ή **defaultValue** αλλιώς. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | Επιστρέφει την τιμή αν βρεθεί· ή **null** αλλιώς, έχει νόημα μόνο για τύπους αναφοράς. |
| [ICollection](../icollection/icollection/)() | Κατασκευαστής προεπιλογής. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Κατασκευαστής αντιγραφής. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Κατασκευαστής μετακίνησης. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | Συνάρτηση πρόσβασης (getter). |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | Συνάρτηση ορισμού (setter). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Εφαρμόζει μια συνάρτηση συσσωρευτή σε μια ακολουθία. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Καθορίζει αν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Καθορίζει αν μια ακολουθία περιέχει οποιαδήποτε στοιχεία. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Καθορίζει αν κάποιο στοιχείο μιας ακολουθίας υπάρχει ή ικανοποιεί μια συνθήκη. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> ) | Συνένωση δύο ακολουθιών. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Καθορίζει αν μια ακολουθία περιέχει μια συγκεκριμένη τιμή. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενο με άμεση μέτρηση). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν την καθορισμένη συνθήκη. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη στην ακολουθία. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη στην ακολουθία. |
| T [LINQ_First](../ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί τη συγκεκριμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο της ακολουθίας, ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή αν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο της ακολουθίας, ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη ελάχιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Αντιστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Μετασχηματίζει τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Μετασχηματίζει καθένα στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>>>&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και ενώνει τις προκύπτουσες ακολουθίες σε μία. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>>>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν καθορισμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου προταστικού. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το lock() statement του C# για κλείδωμα. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Τελεστέας ανάθεσης με μετακίνηση. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Τελεστέας ανάθεσης με μετακίνηση. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Τελεστέας ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Λαμβάνει reverse iterator προς το τελευταίο στοιχείο της συλλογής (πρώτο στο αντίστροφο). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Λαμβάνει reverse iterator προς το τελευταίο στοιχείο της const-προσδιορισμένης συλλογής (πρώτο στο αντίστροφο). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr με αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | Αφαιρεί το κλειδί από το container. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | Διαγράφει το στοιχείο από τη συλλογή. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Λαμβάνει reverse iterator για ένα μη-υπάρχον στοιχείο πριν από την αρχή της συλλογής. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Λαμβάνει reverse iterator για ένα μη-υπάρχον στοιχείο πριν από την αρχή της const-προσδιορισμένης συλλογής. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/)* [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| [SortedDictionary](./sorteddictionary/)() | Δημιουργεί κενό λεξικό. |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>&) | Δημιουργεί κενό λεξικό. |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&) | Κατασκευαστής αντιγραφής. |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&, const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>&) | Κατασκευαστής αντιγραφής. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | Αναζητά την τιμή και την ανακτά αν βρεθεί. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το lock() statement του C# για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/)* [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Λαμβάνει την υλοποίηση του begin const iterator για το τρέχον container. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/)* [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Λαμβάνει την υλοποίηση του begin iterator για το τρέχον container. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/)* [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Λαμβάνει την υλοποίηση του end const iterator για το τρέχον container. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/)* [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Λαμβάνει την υλοποίηση του end iterator για το τρέχον container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [~ICollection](../icollection/~icollection/)() | Καταστροφέας. |
| virtual [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Τύποι ορισμού

| Τύπος ορισμού | Περιγραφή |
| --- | --- |
| [KeyCollection](./keycollection/) | Τύπος συλλογής κλειδιών. |
| [ValueCollection](./valuecollection/) | Τύπος συλλογής τιμών. |
| [map_t](./map_t/) | Βασικός τύπος δεδομένων. |
| [this_t](./this_t/) | Τύπος του εαυτού. |
| [Ptr](./ptr/) | Τύπος δείκτη. |
| [KVPair](./kvpair/) | Τύπος ζεύγους κλειδιού-τιμής. |
| [IEnumerablePtr](./ienumerableptr/) | Συλλογή ίδιων στοιχείων. |
| [IEnumeratorPtr](./ienumeratorptr/) | Τύπος **Enumerator**. |
| [iterator](./iterator/) | Τύπος iterator. |
| [const_iterator](./const_iterator/) | Τύπος const iterator. |
| [reverse_iterator](./reverse_iterator/) | Τύπος reverse iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | Τύπος const reverse iterator. |

## Παρατηρήσεις

Sorted dictionary class wrapping STL map. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## Δείτε επίσης

* Κλάση [BaseDictionary](../basedictionary/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)