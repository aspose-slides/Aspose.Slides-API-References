---
title: ReadAsync()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναγνώνει ασύγχρονα μια ακολουθία byte από το τρέχον ρεύμα, προχωρά τη θέση εντός του ρεύματος κατά τον αριθμό των byte που διαβάστηκαν και παρακολουθεί αιτήματα ακύρωσης.
type: docs
weight: 40
url: /el/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) μέθοδος

Αναγνώνει ασύγχρονα μια ακολουθία byte από το τρέχον ρεύμα, προχωρά τη θέση εντός του ρεύματος κατά τον αριθμό των byte που διαβάστηκαν και παρακολουθεί αιτήματα ακύρωσης.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Παραμέτρους

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γραφτούν τα διαβασμένα byte. |
| offset | **int32_t** | Μία θέση βάσει 0 στο **buffer** από την οποία θα ξεκινήσει η εγγραφή. |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Το διακριτικό για την παρακολούθηση αιτημάτων ακύρωσης. |

### Τιμή Επιστροφής

Μία εργασία (task) που αντιπροσωπεύει την ασύγχρονη λειτουργία ανάγνωσης. Η τιμή της παραμέτρου TResult περιέχει το συνολικό αριθμό των byte που διαβάστηκαν στο buffer. Η τιμή του αποτελέσματος μπορεί να είναι μικρότερη από τον αριθμό των byte που ζητήθηκαν εάν ο αριθμός των διαθέσιμων byte είναι μικρότερος από τον ζητούμενο, ή μπορεί να είναι 0 (μηδέν) εάν έχει φθάσει το τέλος του ρεύματος.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Αναγνώνει ασύγχρονα μια ακολουθία byte από το τρέχον ρεύμα, προχωρά τη θέση εντός του ρεύματος κατά τον αριθμό των byte που διαβάστηκαν και παρακολουθεί αιτήματα ακύρωσης.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Παραμέτρους

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γραφτούν τα διαβασμένα byte. |
| offset | **int32_t** | Μία θέση βάσει 0 στο **buffer** από την οποία θα ξεκινήσει η εγγραφή. |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση. |

### Τιμή Επιστροφής

Μία εργασία (task) που αντιπροσωπεύει την ασύγχρονη λειτουργία ανάγνωσης. Η τιμή της παραμέτρου TResult περιέχει το συνολικό αριθμό των byte που διαβάστηκαν στο buffer. Η τιμή του αποτελέσματος μπορεί να είναι μικρότερη από τον αριθμό των byte που ζητήθηκαν εάν ο αριθμός των διαθέσιμων byte είναι μικρότερος από τον ζητούμενο, ή μπορεί να είναι 0 (μηδέν) εάν έχει φθάσει το τέλος του ρεύματος.

## Δείτε επίσης

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [CancellationToken](../../../system.threading/cancellationtoken/)
* Κλάση [Stream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)