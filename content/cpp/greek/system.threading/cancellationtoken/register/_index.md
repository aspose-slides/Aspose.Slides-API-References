---
title: Register()
second_title: Aspose.Slides για C++ API Reference
description: Καταχωρεί μια callback που θα κληθεί όταν ζητηθεί η ακύρωση.
type: docs
weight: 40
url: /el/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const μέθοδος


Registers a callback that will be invoked when cancellation is requested.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Το Action<> που θα εκτελεστεί όταν ζητηθεί η ακύρωση. |

### Τιμή Επιστροφής

Ένα αντικείμενο [CancellationTokenRegistration](../../cancellationtokenregistration/) που μπορεί να χρησιμοποιηθεί για την ακύρωση της εγγραφής της callback.
## Σχόλια



Εάν έχει ήδη ζητηθεί η ακύρωση, η callback θα κληθεί αμέσως. 

Η callback πρέπει να είναι σύντομη και μη μπλοκαριστική, καθώς θα εκτελεστεί στο νήμα που καλεί τη μέθοδο Cancel() στο [CancellationTokenSource](../../cancellationtokensource/). 

## Δείτε επίσης

* Typedef [Action](../../../system/action/)
* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)