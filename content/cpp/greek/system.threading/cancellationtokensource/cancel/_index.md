---
title: Cancel()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μεταδίδει ένα αίτημα ακύρωσης.
type: docs
weight: 40
url: /el/system.threading/cancellationtokensource/cancel/
---
## μέθοδος CancellationTokenSource::Cancel() method


Communicates a request for cancellation.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Παρατηρήσεις



All registered callbacks will be invoked. 

Subsequent calls to [get_IsCancellationRequested()](../get_iscancellationrequested/) will return true. 

Callbacks are executed synchronously during this call. 

## Δείτε επίσης

* Κλάση [CancellationTokenSource](../)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)