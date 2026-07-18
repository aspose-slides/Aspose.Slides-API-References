---
title: BehaviorPropertyCollection
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει τις ιδιότητες χρονισμού για τη συμπεριφορά του εφέ.
type: docs
weight: 66
url: /el/aspose.slides.animation/behaviorpropertycollection/
---
## BehaviorPropertyCollection κλάση

Αντιπροσωπεύει τις ιδιότητες χρόνου για τη συμπεριφορά του εφέ.

```cpp
class BehaviorPropertyCollection : public Aspose::Slides::Animation::IBehaviorPropertyCollection
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [Add](./add/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | Προσθέτει μια νέα ιδιότητα στη συλλογή. |
| void [Add](./add/)(const [System::String](../../system/string/)\&) override | Προσθέτει μια νέα ιδιότητα στη συλλογή. |
| [iterator](./iterator/) [begin](./begin/)() | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο (αν υπάρχει) της συλλογής. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο (αν υπάρχει) του παράδειγματος της συλλογής που είναι const-ποιημένο. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο που είναι const-ποιημένο (αν υπάρχει) της συλλογής. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει ακριβώς μετά το τελευταίο const-ποιημένο στοιχείο (αν υπάρχει) της συλλογής. |
| void [Clear](./clear/)() override | Αφαιρεί όλες τις ιδιότητες από τη συλλογή. |
| **bool** [Contains](./contains/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) const override | Καθορίζει αν το [ICollection](../../system.collections.generic/icollection/) περιέχει μια συγκεκριμένη τιμή. |
| **bool** [Contains](./contains/)(const [System::String](../../system/string/)\&) const override | Καθορίζει αν το [ICollection](../../system.collections.generic/icollection/) περιέχει μια συγκεκριμένη τιμή. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\>, **int32_t**) override | Αντιγράφει τα στοιχεία του [ICollection](../../system.collections.generic/icollection/) σε ένα [System::Array](../../system/array/), ξεκινώντας από ένα συγκεκριμένο δείκτη [System::Array](../../system/array/). |
| virtual void [CopyTo](../../system.collections.generic/icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Αντιγράφει όλα τα στοιχεία της συλλογής σε υπάρχοντα στοιχεία πίνακα. |
| [iterator](./iterator/) [end](./end/)() | Επιστρέφει έναν επαναλήπτη που δείχνει ακριβώς μετά το τελευταίο στοιχείο (αν υπάρχει) της συλλογής. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Επιστρέφει έναν επαναλήπτη που δείχνει ακριβώς μετά το τελευταίο στοιχείο (αν υπάρχει) του const-προσδιορισμένου παράδειγματος της συλλογής. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με άλλο NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με άλλο NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **int32_t** [get_Count](./get_count/)() const override | Επιστρέφει τον αριθμό των ιδιοτήτων που αποθηκεύονται στη συλλογή. Μόνο-ανάγνωση **int32_t**. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Ελέγχει αν η συλλογή έχει σταθερό μέγεθος. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Επιστρέφει τιμή που υποδεικνύει αν το [ICollection](../../system.collections.generic/icollection/) είναι μόνο-ανάγνωση. Μόνο-ανάγνωση **bool**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Επιστρέφει το αντικείμενο μέσω του οποίου συγχρονίζεται η συλλογή. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Επιστρέφει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\>\> [GetEnumerator](./getenumerator/)() override | Επιστρέφει έναν αλγόριθμο επανάληψης που διασχίζει τη συλλογή. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος του C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Επιστρέφει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση του C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Κατασκευαστής προεπιλογής. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Κατασκευαστής αντιγραφής. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Κατασκευαστής μετακίνησης. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\> [idx_get](./idx_get/)(**int32_t**) const override | Επιστρέφει μια ιδιότητα στον καθορισμένο δείκτη. |
| virtual T [idx_get](../../system.collections.generic/ilist/idx_get/)(int) const | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| void [idx_set](./idx_set/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>) override | Επιστρέφει μια ιδιότητα στον καθορισμένο δείκτη. |
| virtual void [idx_set](../../system.collections.generic/ilist/idx_set/)(int, T) | Ορίζει το στοιχείο στον καθορισμένο δείκτη. |
| **int32_t** [IndexOf](./indexof/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) const override | Καθορίζει τον δείκτη ενός συγκεκριμένου στοιχείου στην [IList](../../system.collections.generic/ilist/). |
| **int32_t** [IndexOf](./indexof/)(const [System::String](../../system/string/)\&) const override | Καθορίζει τον δείκτη ενός συγκεκριμένου στοιχείου βάσει τιμής ιδιότητας στην [IList](../../system.collections.generic/ilist/). |
| void [Insert](./insert/)(**int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | Εισάγει μια νέα ιδιότητα στη συλλογή στον καθορισμένο δείκτη. |
| void [Insert](./insert/)(**int32_t**, [System::String](../../system/string/)) override | Εισάγει μια νέα ιδιότητα (με την καθορισμένη τιμή ιδιότητας) στη συλλογή στον καθορισμένο δείκτη. |
| virtual void [Insert](../../system.collections.generic/ilist/insert/)(int, const T\&) | Εισάγει το στοιχείο στην καθορισμένη θέση, μετατοπίζοντας τα άλλα στοιχεία. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Εφαρμόζει μια συνάρτηση συσσωμάτωσης σε μια ακολουθία. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει αν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Καθορίζει αν μια ακολουθία περιέχει στοιχεία. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει αν κάποιο στοιχείο μιας ακολουθίας υπάρχει ή ικανοποιεί μια συνθήκη. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Συνενώνει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Καθορίζει αν μια ακολουθία περιέχει μια συγκεκριμένη τιμή. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενο με άμετρη μέτρηση). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν τη συγκεκριμένη συνθήκη. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε έναν καθορισμένο δείκτη σε μια ακολουθία. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί τη συγκεκριμένη συνθήκη. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά βάσει των τιμών κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά βάσει των τιμών κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Αντιστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Μετασχηματίζει τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το δείκτη του στοιχείου. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν ορισμένο αριθμό συνεχόμενων στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου καταλογιστικού. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιείται το αντικείμενο φυλάκιο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος του C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί το νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Χειριστής μετακίνησης ανάθεσης. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Χειριστής μετακίνησης ανάθεσης. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Χειριστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί το νέο αντικείμενο και επιτρέπει την αντιγραφή των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr με βάση την αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| **bool** [Remove](./remove/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή. |
| **bool** [Remove](./remove/)(const [System::String](../../system/string/)\&) override | Αφαιρεί την καθορισμένη ιδιότητα από τη συλλογή. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Αφαιρεί την ιδιότητα στον καθορισμένο δείκτη. |
| virtual void [RemoveAt](../../system.collections.generic/ilist/removeat/)(int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα πρότυπου σε αδρή δεικτοδότηση (αντί για κοινόχρηστη). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδρή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Επιστρέφει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος του C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιείται το αντικείμενο φυλάκιο [LockContext](../../system/lockcontext/). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο (αν υπάρχει) του const-προσδιορισμένου παράδειγματος της συλλογής. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Επιστρέφει έναν επαναλήπτη που δείχνει στο πρώτο στοιχείο (αν υπάρχει) της συλλογής. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Επιστρέφει έναν επαναλήπτη που δείχνει ακριβώς μετά το τελευταίο στοιχείο (αν υπάρχει) του const-προσδιορισμένου παράδειγματος της συλλογής. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | Επισ retourne... (actually: ) Επιστρέφει έναν επαναλήπτη που δείχνει ακριβώς μετά το τελευταίο στοιχείο (αν υπάρχει) της συλλογής. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδρή μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδρή μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Καταστροφέας. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | Τύπος συλλογής του οποίου οι τύποι επαναλήπτη χρησιμοποιούνται ως τύποι επαναλήπτη στην τρέχουσα συλλογή. |
| [iterator](./iterator/) | Τύπος επαναλήπτη. |
| [const_iterator](./const_iterator/) | Τύπος const επαναλήπτη. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Τύπος εικονικοποιημένου στοιχείου. |
| [virtualized_iterator](./virtualized_iterator/) | Τύπος εικονικοποιημένου. |

## Δείτε επίσης

* Κλάση [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)
* Χώρος ονομάτων [Aspose::Slides::Animation](../)
* Βιβλιοθήκη [Aspose.Slides](../../)