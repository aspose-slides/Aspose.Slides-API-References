---
title: Task()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα Task με μια ενέργεια για εκτέλεση.
type: docs
weight: 1
url: /el/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) constructor


Δημιουργεί ένα [Task](../) με μια ενέργεια για εκτέλεση.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Η ενέργεια που θα εκτελεστεί ασύγχρονα |

## Task::Task(const Action<>\&, const CancellationToken\&) constructor


Δημιουργεί ένα [Task](../) με μια ενέργεια και διακριτικό ακύρωσης.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Η ενέργεια που θα εκτελεστεί ασύγχρονα |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Διακριτικό για παρακολούθηση αιτημάτων ακύρωσης |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\>) constructor


Δημιουργεί ένα [Task](../) με μια ενέργεια με κατάσταση και αντικείμενο κατάστασης.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Η ενέργεια που θα εκτελεστεί (δέχεται αντικείμενο κατάστασης) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Αντικείμενο κατάστασης ορισμένο από τον χρήστη που περνιέται στην ενέργεια |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor


Δημιουργεί ένα [Task](../) με ενέργεια με κατάσταση, κατάσταση και διακριτικό ακύρωσης.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Η ενέργεια που θα εκτελεστεί (δέχεται αντικείμενο κατάστασης) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Αντικείμενο κατάστασης ορισμένο από τον χρήστη που περνιέται στην ενέργεια |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Διακριτικό για παρακολούθηση αιτημάτων ακύρωσης |

## Task::Task() constructor


Εσωτερικός κατασκευαστής για δημιουργία μη αρχικοποιημένων εργασιών.

```cpp
System::Threading::Tasks::Task::Task()
```

## Δείτε επίσης

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Task](../)
* Κλάση [CancellationToken](../../../system.threading/cancellationtoken/)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)