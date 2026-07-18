---
title: AreFPandArithmetic
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει αν το T1 είναι αριθμητικός και το T2 είναι πλωτής υποδιαστολής, ή το αντίστροφο. Σε αυτή την περίπτωση, ορίζει το μέλος value σε true, διαφορετικά είναι false.
type: docs
weight: 79
url: /el/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Ελέγχει αν το **T1** είναι αριθμητικός και το **T2** είναι πλωτής υποδιαστολής, ή το αντίστροφο. Σε αυτή την περίπτωση, ορίζει το μέλος value σε αληθές, διαφορετικά είναι ψευδές.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Δείτε επίσης

* Χώρος ονομάτων [System::TestPredicates::TypeTraits](../)
* Βιβλιοθήκη [Aspose.Slides](../../)