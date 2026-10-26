---
title: ReadAsync()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναγνώζει ασύγχρονα μια ακολουθία byte από το τρέχον ρεύμα, προωθεί τη θέση στο ρεύμα κατά τον αριθμό των αναγνωσμένων byte και παρακολουθεί αιτήματα ακύρωσης.
type: docs
weight: 196
url: /el/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) μέθοδος

Αναγνώσκει ασύγχρονα μια ακολουθία byte από το τρέχον ρεύμα, προωθεί τη θέση στο ρεύμα κατά τον αριθμό των αναγνωσμένων byte και παρακολουθεί αιτήματα ακύρωσης.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο δέκτης byte στον οποίο θα γραφούν τα αναγνωσμένα byte. |
| offset | **int32_t** | Μία θέση με βάση το 0 στο **buffer** από την οποία θα αρχίσει η εγγραφή. |
| count | **int32_t** | Ο αριθμός των byte που θα διαβαστούν. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Το token που παρακολουθείται για αιτήματα ακύρωσης. |

### Τιμή Επιστροφής

Μια εργασία (task) που αντιπροσωπεύει την ασύγχρονη λειτουργία ανάγνωσης. Η τιμή της παραμέτρου TResult περιέχει τον συνολικό αριθμό των byte που διαβάστηκαν στο buffer. Η τιμή του αποτελέσματος μπορεί να είναι μικρότερη από τον αριθμό των ζητούμενων byte αν ο τρέχων αριθμός διαθέσιμων byte είναι μικρότερος από τον ζητούμενο, ή μπορεί να είναι 0 (μηδέν) αν έχει φτάσει το τέλος του ρεύματος.

## Δείτε επίσης

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)