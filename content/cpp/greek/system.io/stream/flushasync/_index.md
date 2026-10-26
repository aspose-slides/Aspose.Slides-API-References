---
title: FlushAsync()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθαρίζει ασύγχρονα όλες τις προσωρινές μνήμες (buffers) για αυτό το stream, προκαλεί την εγγραφή τυχόν δεδομένων που είναι αποθηκευμένα στο buffer στη βασική συσκευή και παρακολουθεί αιτήματα ακύρωσης.
type: docs
weight: 118
url: /el/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) μέθοδος

Καθαρίζει ασύγχρονα όλες τις προσωρινές μνήμες (buffers) για αυτό το stream, προκαλεί την εγγραφή τυχόν δεδομένων που είναι αποθηκευμένα στο buffer στη βασική συσκευή και παρακολουθεί αιτήματα ακύρωσης.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Το token για την παρακολούθηση των αιτημάτων ακύρωσης. |

### Τιμή Επιστροφής

Μια εργασία που αντιπροσωπεύει την ασύγχρονη λειτουργία εκκαθάρισης.

## Stream::FlushAsync() μέθοδος

Καθαρίζει ασύγχρονα όλες τις προσωρινές μνήμες (buffers) για αυτό το stream, προκαλεί την εγγραφή τυχόν δεδομένων που είναι αποθηκευμένα στο buffer στη βασική συσκευή και παρακολουθεί αιτήματα ακύρωσης.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### Τιμή Επιστροφής

Μια εργασία που αντιπροσωπεύει την ασύγχρονη λειτουργία εκκαθάρισης.

## Δείτε επίσης

* Typedef [TaskPtr](../../../system/taskptr/)
* Κλάση [CancellationToken](../../../system.threading/cancellationtoken/)
* Κλάση [Stream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)