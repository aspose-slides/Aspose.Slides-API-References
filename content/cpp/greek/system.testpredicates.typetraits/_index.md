---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides για C++ API Αναφορά
description: 
type: docs
weight: 963
url: /el/system.testpredicates.typetraits/
---
## Δομές

| Δομή | Περιγραφή |
| --- | --- |
| [has_data_method](./has_data_method/) | Ελέγχει αν ένας τύπος έχει τη μέθοδο data(). Αν το κάνει, κληρονομεί std::true_type, διαφορετικά κληρονομεί std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Εξειδίκευση για τον τύπο BitArray που παρέχει τύπο boost ο οποίος δεν είναι προσβάσιμος εκεί. |
| [has_print_to_method](./has_print_to_method/) | Ελέγχει την υπερφόρτωση της συνάρτησης PrintTo που δέχεται τον δεδομένο τύπο ως πρώτο όρισμα. Αν υπάρχει υπερφόρτωση, κληρονομεί std::true_type, διαφορετικά κληρονομεί std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Ελέγχει αν ένας συγκεκριμένος τύπος είναι κοντέινερ τύπου STL. Για να το κάνει, ελέγχει την ύπαρξη των τύπων μέλους iterator και const_iterator. Αν και οι δυο υπάρχουν, κληρονομεί std::true_type, διαφορετικά κληρονομεί std::false_type. |
| [IsEnumerable](./isenumerable/) | Ελέγχει αν ο τύπος έχει εξειδίκευση [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) ως βασικό τύπο. Εάν ναι, το μέλος value ορίζεται σε true, διαφορετικά ορίζεται σε false. |
| [LargestFPType](./largestfptype/) | Παρέχει ψευδώνυμο για τον μεγαλύτερο τύπο κινητής υποδιαστολής που παρέχεται. Αγνοεί τύπους που δεν είναι κινητής υποδιαστολής. |

## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Ελέγχει ότι το **T1** είναι αριθμητικός και το **T2** είναι τύπος κινητής υποδιαστολής, ή το αντίστροφο. Εάν ναι, ορίζει το μέλος value σε true, διαφορετικά είναι false. |
| [AnyOfDecimal](./anyofdecimal/) | Ελέγχει ότι τουλάχιστον ένα από τα ορίσματα τύπου είναι [System::Decimal](../system/decimal/). Εάν ναι, ορίζει το μέλος value σε true, διαφορετικά είναι false. |
| [IsArray](./isarray/) | Ελέγχει αν ο τύπος είναι εξειδίκευση [System::Array](../system/array/). Εάν ναι, το μέλος value ορίζεται σε true, διαφορετικά ορίζεται σε false. |
| [IsList](./islist/) | Ελέγχει αν ο τύπος είναι εξειδίκευση [System::Collections::Generic::List](../system.collections.generic/list/). Εάν ναι, το μέλος value ορίζεται σε true, διαφορετικά ορίζεται σε false. |
| [BothArrayOrList](./botharrayorlist/) | Ελέγχει αν και τα δύο ορίσματα τύπου είναι πίνακες ή λίστες. Εάν ναι, το μέλος value ορίζεται σε true, διαφορετικά ορίζεται σε false. |
| [BothEnumerable](./bothenumerable/) | Ελέγχει αν και τα δύο ορίσματα τύπου είναι IEnumerable. Εάν ναι, το μέλος value ορίζεται σε true, διαφορετικά ορίζεται σε false. |