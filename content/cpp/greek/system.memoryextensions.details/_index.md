---
title: "System::MemoryExtensions::Details"
second_title: Aspose.Slides για C++ API Αναφορά
description: 
type: docs
weight: 638
url: /el/system.memoryextensions.details/
---
## Συναρτήσεις

| Συνάρτηση | Περιγραφή |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | Συγκρίνει δύο έξυπνα δείκτες. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | Συγκρίνει δύο αριθμητικές τιμές. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | Συγκρίνει έναν έξυπνο δείκτη με μια τιμή. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | Βρίσκει το τελευταίο δείκτη μιας τιμής σε ένα εύρος. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ελέγχει αν δύο εύρη είναι ίσα ξεκινώντας από τις καθορισμένες θέσεις. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Εσωτερική υλοποίηση του αλγόριθμου introsort για ζεύγη κλειδιού-τιμής. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | Ανταλλάσσει ζεύγη κλειδιού-τιμής εάν πληρούται η συνθήκη σύγκρισης. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Εκτελεί ταξινόμηση εισαγωγής στα ζεύγη κλειδιού-τιμής. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Εκτελεί ταξινόμηση σωρού στα ζεύγη κλειδιού-τιμής. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Διατηρεί την ιδιότητα του σωρού για τα ζεύγη κλειδιού-τιμής. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Επιλέγει άξονα και διαιρεί τα ζεύγη κλειδιού-τιμής για quicksort. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | Κοινή υλοποίηση δυαδικής αναζήτησης. |