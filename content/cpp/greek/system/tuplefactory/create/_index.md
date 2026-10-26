---
title: Create()
second_title: Αναφορά API του Aspose.Slides για C++ 
description: Δημιουργεί ένα νέο αντικείμενο πλειάδας.
type: docs
weight: 1
url: /el/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) μέθοδος

Δημιουργεί ένα νέο αντικείμενο πλειάδας.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) μέθοδος

Δημιουργεί μια νέα 8-πλειάδα. Το 8ο στοιχείο αποθηκεύεται μέσα στο [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Tuple](../../tuple/)
* Κλάση [TupleFactory](../)
* Ονομαχώρος [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)