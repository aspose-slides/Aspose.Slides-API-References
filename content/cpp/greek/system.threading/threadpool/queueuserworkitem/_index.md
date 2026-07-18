---
title: QueueUserWorkItem()
second_title: Αναφορά API του Aspose.Slides για C++
description: Τοποθετεί το στοιχείο εργασίας στην ουρά που είναι διαθέσιμο με κλήση επιστροφής χωρίς παράμετρο.
type: docs
weight: 14
url: /el/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) μέθοδος


Τοποθετεί το στοιχείο εργασίας στην ουρά που είναι διαθέσιμο με μια κλήση επιστροφής χωρίς παράμετρο.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |

### Τιμή Επιστροφής

Πάντα επιστρέφει true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) μέθοδος


Τοποθετεί το στοιχείο εργασίας στην ουρά που είναι διαθέσιμο με μια κλήση επιστροφής χωρίς παράμετρο.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Job function parameter. |

### Τιμή Επιστροφής

Πάντα επιστρέφει true.

## Δείτε επίσης

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ThreadPool](../)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)