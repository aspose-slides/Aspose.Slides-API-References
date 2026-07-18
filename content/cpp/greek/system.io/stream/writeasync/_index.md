---
title: WriteAsync()
second_title: Aspose.Slides για C++ API Αναφορά
description: Γράφει ασύγχρονα μια ακολουθία byte στη τρέχουσα ροή, προωθεί τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των byte που γράφτηκαν και παρακολουθεί αιτήματα ακύρωσης.
type: docs
weight: 66
url: /el/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Γράφει ασύγχρονα μια ακολουθία bytes στο τρέχον stream, προωθεί τη τρέχουσα θέση μέσα σε αυτό το stream κατά τον αριθμό των bytes που γράφτηκαν και παρακολουθεί αιτήματα ακύρωσης.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα bytes προς εγγραφή. |
| offset | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** όπου αρχίζει το υποεύρος για εγγραφή. |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποεύρος προς εγγραφή. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Το διακριτικό για την παρακολούθηση αιτημάτων ακύρωσης. |

### Τιμή Επιστροφής

Μία εργασία (task) που αντιπροσωπεύει τη διαδικασία ασύγχρονης εγγραφής.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Γράφει ασύγχρονα μια ακολουθία bytes στο τρέχον stream, προωθεί τη τρέχουσα θέση μέσα σε αυτό το stream κατά τον αριθμό των bytes που γράφτηκαν και παρακολουθεί αιτήματα ακύρωσης.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα bytes προς εγγραφή. |
| offset | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** όπου αρχίζει το υποεύρος για εγγραφή. |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποεύρος προς εγγραφή. |

### Τιμή Επιστροφής

Μία εργασία (task) που αντιπροσωπεύει τη διαδικασία ασύγχρονης εγγραφής.

## Δείτε επίσης

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)