---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί μια συνδεμένη πηγή token που ακυρώνεται όταν οποιοδήποτε από τα παρεχόμενα token ακυρωθεί.
type: docs
weight: 66
url: /el/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method

Δημιουργεί μια συνδεδεμένη πηγή token που ακυρώνεται όταν οποιοδήποτε από τα παρεχόμενα token ακυρωθεί.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Πρώτο token ακύρωσης για παρακολούθηση. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Δεύτερο token ακύρωσης για παρακολούθηση. |

### Τιμή Επιστροφής

Νέα πηγή token που θα ακυρωθεί όταν οποιοδήποτε από τα εισαγόμενα token ακυρωθεί.

## Παρατηρήσεις

Η επιστρεφόμενη πηγή θα ακυρωθεί άμεσα εάν οποιοδήποτε από τα εισαγόμενα token είναι ήδη ακυρωμένο. 

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CancellationTokenSource](../)
* Class [CancellationToken](../../cancellationtoken/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)