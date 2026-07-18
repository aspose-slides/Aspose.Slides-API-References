---
title: Handle()
second_title: Aspose.Slides για την Αναφορά API C++
description: Καλεί μια συνάρτηση χειριστή για κάθε εσωτερική εξαίρεση και επαναδηλώνει τυχόν μη επεξεργασμένες εξαιρέσεις.
type: docs
weight: 66
url: /el/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) method


Καλεί μια συνάρτηση διαχειριστή για κάθε εσωτερική εξαίρεση και επαναδηλώνει τυχόν μη επεξεργασμένες εξαιρέσεις.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Μια συνάρτηση που λαμβάνει μια Exception και επιστρέφει true εάν αυτή έχει υποστεί επεξεργασία. |
## Παρατηρήσεις



Εάν όλες οι εξαιρέσεις έχουν υποστεί επεξεργασία, η μέθοδος επιστρέφει κανονικά· διαφορετικά, ρίχνεται μια νέα AggregateException που περιέχει τις μη επεξεργασμένες εξαιρέσεις. 

## Δείτε επίσης

* Typedef [Exception](../../exception/)
* Κλάση [Func](../../func/)
* Κλάση [Details_AggregateException](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)