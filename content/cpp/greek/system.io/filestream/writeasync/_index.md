---
title: WriteAsync()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ασύγχρονα γράφει μια ακολουθία byte στη τρέχουσα ροή, προχωρά τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των γραμμένων byte, και παρακολουθεί τις αιτήσεις ακύρωσης.
type: docs
weight: 261
url: /el/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) μέθοδος

Γράφει ασύγχρονα μια ακολουθία byte στη τρέχουσα ροή, προχωρά τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των γραμμένων byte, και παρακολουθεί τις αιτήσεις ακύρωσης.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή. |
| offset | **int32_t** | Ένας δείκτης 0-βάσης του στοιχείου στο **buffer** όπου αρχίζει το υποσύνολο για εγγραφή. |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο για εγγραφή. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Το διακριτικό για την παρακολούθηση των αιτήσεων ακύρωσης. |

### Τιμή Επιστροφής

Μία εργασία που αντιπροσωπεύει την ασύγχρονη λειτουργία εγγραφής.

## Δείτε επίσης

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [CancellationToken](../../../system.threading/cancellationtoken/)
* Κλάση [FileStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)