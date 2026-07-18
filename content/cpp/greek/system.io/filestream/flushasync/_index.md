---
title: FlushAsync()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ασυγχρόνως εκκαθαρίζει όλες τις προσωρινές μνήμες για αυτή τη ροή, προκαλεί την εγγραφή τυχόν δεδομένων που είναι στο buffer στη βασική συσκευή και παρακολουθεί αιτήματα ακύρωσης.
type: docs
weight: 157
url: /el/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) μέθοδος

Ασύγχρονα εκκαθαρίζει όλα τα buffers για αυτό το stream, προκαλεί την εγγραφή τυχόν δεδομένων που είναι στο buffer στη βασική συσκευή και παρακολουθεί αιτήματα ακύρωσης.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Το token για την παρακολούθηση αιτημάτων ακύρωσης. |

### Τιμή Επιστροφής

Μια εργασία που αντιπροσωπεύει την ασύγχρονη λειτουργία εκκαθάρισης.

## Δείτε επίσης

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)