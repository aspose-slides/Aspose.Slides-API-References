---
title: LinkedList
second_title: Aspose.Slides για C++ API Αναφορά
description: Προκαθορισμένη δήλωση LinkedList.
type: docs
weight: 404
url: /el/system.collections.generic/linkedlist/
---
## LinkedList κλάση


[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Τύπος τιμής που περιέχεται. |
## Methods

| Method | Description |
| --- | --- |
| void [Add](./add/)(const T\&) override | Προσθέτει **element** στο τέλος της λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | Προσθέτει **element** μετά από **node** της λίστας. |
| void [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | Προσθέτει **newNode** μετά από **node** της λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | Προσθέτει **element** πριν από **node** της λίστας. |
| void [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | Προσθέτει **newNode** πριν από **node** της λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddFirst](./addfirst/)(const T\&) | Προσθέτει **element** στην αρχή της λίστας. |
| void [AddFirst](./addfirst/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | Προσθέτει **newNode** στην αρχή της λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddLast](./addlast/)(const T\&) | Προσθέτει **element** στο τέλος της λίστας. |
| void [AddLast](./addlast/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | Προσθέτει **newNode** στο τέλος της λίστας. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Επιστρέφει επαναλήπτη προς το πρώτο στοιχείο της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Επιστρέφει επαναλήπτη προς το πρώτο στοιχείο της const-πυκνωμένης συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Επιστρέφει επαναλήπτη προς το πρώτο const-πυκνωμένο στοιχείο της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Επιστρέφει επαναλήπτη για ένα ανύπαρκτο const-πυκνωμένο στοιχείο πίσω από το τέλος της συλλογής. |
| void [Clear](./clear/)() override | Διαγράφει όλα τα στοιχεία της λίστας. |
| **bool** [Contains](./contains/)(const T\&) const override | Ελέγχει αν το **element** υπάρχει στη λίστα. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Αντιγράφει τα δεδομένα του container σε υπάρχοντα στοιχεία πίνακα. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Επιστρέφει αντίστροφο επαναλήπτη προς το τελευταίο const-πυκνωμένο στοιχείο της συλλογής (πρώτο σε αντίστροφη σειρά). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Επιστρέφει αντίστροφο επαναλήπτη για ένα ανύπαρκτο const-πυκνωμένο στοιχείο πριν από την αρχή της συλλογής. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Επιστρέφει επαναλήπτη για ένα ανύπαρκτο στοιχείο πίσω από το τέλος της συλλογής. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Επιστρέφει επαναλήπτη για ένα ανύπαρκτο στοιχείο πίσω από το τέλος της const-πυκνωμένης συλλογής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Για εσωτερική χρήση μόνο. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [Find](./find/)(const T\&) const | Εκτελεί προώθηση αναζήτησης ενός **element** στη λίστα. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [FindLast](./findlast/)(const T\&) const | Εκτελεί αντίστροφη αναζήτηση ενός **element** στη λίτα. |
| int [get_Count](./get_count/)() const override | Επιστρέφει τον αριθμό των στοιχείων στη λίστα. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_First](./get_first/)() const | Επιστρέφει δείκτη προς το πρώτο στοιχείο της λίστας. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ελέγχει αν η συλλογή είναι μόνο για ανάγνωση. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_Last](./get_last/)() const | Επιστρέφει δείκτη προς το τελευταίο στοιχείο της λίστας. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Επιστρέφει το αντικείμενο μέσω του οποίου η συλλογή συγχρονίζεται. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Επιστρέφει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() override | Επιστρέφει enumerator για την επανάληψη του τρέχοντος [LinkedList](./). |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Επιστρέφει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Προεπιλεγμένος κατασκευαστής. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Κατασκευαστής αντιγραφής. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Κατασκευαστής μετακίνησης. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# «is». |
|  [LinkedList](./linkedlist/)() | Δημιουργεί κενό [LinkedList](./). |
|  [LinkedList](./linkedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>\&) | Κατασκευαστής αντιγραφής. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει μια συνάρτηση συγκεντρωτή σε μια ακολουθία. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει αν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Καθορίζει αν μια ακολουθία περιέχει στοιχεία. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει αν κάποιο στοιχείο της ακολουθίας υπάρχει ή ικανοποιεί μια συνθήκη. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Συγχωνεύει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Καθορίζει αν μια ακολουθία περιέχει την καθορισμένη τιμή. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενο με άμεση καταμέτρηση). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν την καθορισμένη συνθήκη. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο στη συγκεκριμένη θέση στην ακολουθία. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο στη συγκεκριμένη θέση στην ακολουθία. |
| T [LINQ_First](../ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο της ακολουθίας. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί τη συνθήκη. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο της ακολουθίας ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι άδεια. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί τη συνθήκη ή μια προεπιλεγμένη τιμή αν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο της ακολουθίας. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο της ακολουθίας ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι άδεια. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο της γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο της γενικής ακολουθίας και επιστρέφει την ελάχιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία της ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγει το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία της ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγει το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Αντιστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Μετασχηματίζει στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Εμφανίζει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Επιστρέφει καθορισμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Δημιουργεί πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Δημιουργεί List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου προβλέψιμου. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη λειτουργία κλειδώματος C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τρόπος ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκατηγοριών. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Τρόπος ανάθεσης κίνησης. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Τρόπος ανάθεσης κίνησης. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Επιστρέφει αντίστροφο επαναλήπτη προς το τελευταίο στοιχείο της συλλογής (πρώτο σε αντίστροφη σειρά). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Επιστρέφει αντίστροφο επαναλήπτη προς το τελευταίο const-πυκνωμένο στοιχείο της συλλογής (πρώτο σε αντίστροφη σειρά). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνετε αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| **bool** [Remove](./remove/)(const T\&) override | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου **element** από τη λίστα. |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | Αφαιρεί κόμβο από τη λίστα. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [RemoveFirst](./removefirst/)() | Αφαιρεί τον πρώτο κόμβο από τη λίστα. |
| void [RemoveLast](./removelast/)() | Αφαιρεί τον τελευταίο κόμβο από τη λίστα. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Επιστρέφει αντίστροφο επαναλήπτη για ένα ανύπαρκτο στοιχείο πριν από την αρχή της συλλογής. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Επιστρέφει αντίστροφο επαναλήπτη για ένα ανύπαρκτο στοιχείο πριν από την αρχή της const-πυκνωμένης συλλογής. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει τον n-οστό παράμετρο προτύπου ως αδύναμο δείκτη (αντί για shared). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Επιστρέφει τη τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Επιστρέφει την υλοποίηση του const-begin επαναλήπτη για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Επιστρέφει την υλοποίηση του begin επαναλήπτη για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Επιστρέφει την υλοποίηση του const-end επαναλήπτη για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Επιστρέφει την υλοποίηση του end επαναλήπτη για το τρέχον container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [list_t](./list_t/) | Βασικός τύπος δεδομένων. |
| [iterator](./iterator/) | Τύπος επαναλήπτη. |
| [const_iterator](./const_iterator/) | Τύπος const-επαναλήπτη. |
| [reverse_iterator](./reverse_iterator/) | Τύπος αντίστροφου επαναλήπτη. |
| [const_reverse_iterator](./const_reverse_iterator/) | Τύπος const-αντίστροφου επαναλήπτη. |
## Remarks


Δοχέας συνδεδεμένης λίστας. Υλοποιεί ένα περιτύλιγμα πάνω από std::list. Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε δείγμα αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιτυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτό το δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα.


```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Δημιουργεί ένα αντικείμενο της κλάσης LinkedList.
  auto list = MakeObject<LinkedList<int>>();

  // Συμπληρώνει τη συνδεδεμένη λίστα.
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // Εκτυπώνει τα στοιχεία της συνδεδεμένης λίστας.
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
1 15 25 30
*/
```

## See Also

* Κλάση [Object](../../system/object/)
* Κλάση [ICollection](../icollection/)
* Κλάση [Invalidatable](../../system.collections/invalidatable/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)