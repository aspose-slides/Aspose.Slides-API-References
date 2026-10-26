---
title: Run()
second_title: Aspose.Slides για C++ Αναφορά API
description: Τοποθετεί την καθορισμένη εργασία στην ουρά για εκτέλεση στην ομάδα νημάτων και επιστρέφει μια αναφορά Task για αυτήν την εργασία.
type: docs
weight: 157
url: /el/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) συνάρτηση

Τοποθετεί την καθορισμένη εργασία στην ουρά για εκτέλεση στην ομάδα νημάτων και επιστρέφει μια [Task](../task/) αναφορά για αυτήν την εργασία.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Η εργασία που θα εκτελεστεί ασύγχρονα. |

### Τιμή επιστροφής

Μια [Task](../task/) που αντιπροσωπεύει την εργασία που τοποθετήθηκε στην ουρά για εκτέλεση στην ομάδα νημάτων.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) συνάρτηση

Τοποθετεί την καθορισμένη εργασία στην ουρά για εκτέλεση στην ομάδα νημάτων και επιστρέφει μια [Task](../task/) αναφορά για αυτήν την εργασία.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Η εργασία που θα εκτελεστεί ασύγχρονα. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Ένα διακριτικό ακύρωσης που μπορεί να χρησιμοποιηθεί για την ακύρωση της εργασίας εάν δεν έχει ακόμη ξεκινήσει. |

### Τιμή επιστροφής

Μια [Task](../task/) που αντιπροσωπεύει την εργασία που τοποθετήθηκε στην ουρά για εκτέλεση στην ομάδα νημάτων.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) συνάρτηση

Τοποθετεί την καθορισμένη εργασία στην ουρά για εκτέλεση στην ομάδα νημάτων και επιστρέφει έναν διαμεσολαβητή για το [Task](../task/) που επιστρέφεται από τη συνάρτηση.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Η εργασία που θα εκτελεστεί ασύγχρονα, η οποία επιστρέφει ένα [Task](../task/). |

### Τιμή επιστροφής

Μια [Task](../task/) που αντιπροσωπεύει έναν διαμεσολαβητή για το [Task](../task/) που επιστρέφεται από τη συνάρτηση.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) συνάρτηση

Τοποθετεί την καθορισμένη εργασία στην ουρά για εκτέλεση στην ομάδα νημάτων και επιστρέφει μια αναφορά Task<TResult> για αυτήν την εργασία.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TResult | Ο τύπος του αποτελέσματος που επιστρέφεται από την εργασία. |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Η εργασία που θα εκτελεστεί ασύγχρονα. |

### Τιμή επιστροφής

Μια Task<TResult> που αντιπροσωπεύει την εργασία που τοποθετήθηκε στην ουρά για εκτέλεση στην ομάδα νημάτων.

## Δείτε επίσης

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Κλάση [CancellationToken](../../system.threading/cancellationtoken/)
* Κλάση [Func](../../system/func/)
* Χώρος ονομάτων [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)