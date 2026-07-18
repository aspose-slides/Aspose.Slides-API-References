---
title: "System::Collections::Generic::Details"
second_title: Αναφορά API του Aspose.Slides για C++
description: 
type: docs
weight: 352
url: /el/system.collections.generic.details/
---
## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Απαράβατος χρησιμοποιείται από τις μεθόδους επέκτασης IEnumerable.Cast() και IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Απαράβατος χρησιμοποιείται από τη μέθοδο επέκτασης IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Απαριθμητής χρησιμοποιείται από τη μέθοδο επέκτασης IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Απαριθμητής χρησιμοποιείται από τη μέθοδο επέκτασης IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Απαριθμητής χρησιμοποιείται από τη μέθοδο επέκτασης IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Δομές

| Δομή | Περιγραφή |
| --- | --- |
| [ComparerType](./comparertype/) | Συγκρίνει στοιχεία χρησιμοποιώντας τη σημασιολογία 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Συγκρίνει στοιχεία χρησιμοποιώντας τη σημασιολογία 'less'. |
| [has_method_compareto](./has_method_compareto/) | Ελέγχει εάν η μέθοδος CompareTo υπάρχει στον καθορισμένο τύπο. Εάν ναι, κληρονομεί std::true_type, αλλιώς κληρονομεί std::false_type. Μπορεί να χρησιμοποιηθεί σε std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Ελέγχει εάν η μέθοδος CompareTo(SharedPtr<T>) υπάρχει στον καθορισμένο τύπο. Εάν ναι, κληρονομεί std::true_type, αλλιώς κληρονομεί std::false_type. Μπορεί να χρησιμοποιηθεί σε std::enable_if. |
| [IsEqualExist](./isequalexist/) | Ελέγχει εάν ο τύπος παρέχει τον τελεστή ==. |
## Συναρτήσεις

| Συνάρτηση | Περιγραφή |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Ελέγχει εάν το ευρετήριο είναι εκτός των ορίων του container, εξαιρουμένου του μεγέθους του container. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Ελέγχει εάν το ευρετήριο είναι εκτός των ορίων του container, εξαιρουμένου του μεγέθους του container. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Ελέγχει εάν το ευρετήριο είναι εκτός των ορίων του container, συμπεριλαμβανομένου του μεγέθους του container. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Ελέγχει εάν το ευρετήριο είναι εκτός των ορίων του container, συμπεριλαμβανομένου του μεγέθους του container. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Βοηθητική συνάρτηση για τον καθορισμό εάν η συγκεκριμένη κλάση έχει τον τελεστή ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Βοηθητική συνάρτηση για τον καθορισμό εάν η συγκεκριμένη κλάση έχει τον τελεστή ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Προσπαθεί να πάρει το πρώτο στοιχείο της συλλογής. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Προσπαθεί να πάρει το πρώτο στοιχείο της συλλογής, το οποίο ικανοποιεί τη συνάρτηση predicate. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Προσπαθεί να πάρει το τελευταίο στοιχείο της συλλογής. |
## Typedefs

| Typedef | Περιγραφή |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Ψεύτικο typedef για να ελέγξει την ύπαρξη του τελεστή ==. |