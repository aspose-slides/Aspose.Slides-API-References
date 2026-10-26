---
title: Compare()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συγκρίνει δύο τιμές.
type: docs
weight: 2692
url: /el/system/compare/
---
## System::Compare(const TA\&, const TB\&) συνάρτηση

Συγκρίνει δύο τιμές.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TA | Ο τύπος του πρώτου συγκριτικού |
| TB | Ο τύπος του δεύτερου συγκριτικού |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const TA\& | Το πρώτο συγκριτικό |
| b | const TB\& | Το δεύτερο συγκριτικό |

### Τιμή επιστροφής

- 1 εάν **a** είναι μικρότερο από **b**· 0 εάν οι τιμές είναι ίσες· 1 εάν **a** είναι μεγαλύτερο από **b**

## System::Compare(const TA\&, const TB\&) συνάρτηση

Συγκρίνει δύο τιμές κινητής υποδιαστολής.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TA | Ο τύπος του πρώτου συγκριτικού |
| TB | Ο τύπος του δεύτερου συγκριτικού |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const TA\& | Το πρώτο συγκριτικό |
| b | const TB\& | Το δεύτερο συγκριτικό |

### Τιμή επιστροφής

- 1 εάν **a** είναι μικρότερο από **b**· 0 εάν οι τιμές είναι ίσες· 1 εάν **a** είναι μεγαλύτερο από **b**

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)