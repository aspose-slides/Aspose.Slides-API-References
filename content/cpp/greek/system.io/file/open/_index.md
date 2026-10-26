---
title: Open()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανοίγει το καθορισμένο αρχείο στη συγκεκριμένη λειτουργία για ανάγνωση και εγγραφή χωρίς κοινή χρήση.
type: docs
weight: 235
url: /el/system.io/file/open/
---
## File::Open(const String\&, FileMode) μέθοδος

Ανοίγει το συγκεκριμένο αρχείο στη δηλωμένη λειτουργία για ανάγνωση και εγγραφή χωρίς κοινή χρήση.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου προς άνοιγμα |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία με την οποία θα ανοίξει το αρχείο |

### Τιμή Επιστροφής

Ένα αντικείμενο [FileStream](../../filestream/) που σχετίζεται με το ανοιγμένο αρχείο

## File::Open(const String\&, FileMode, FileAccess, FileShare) μέθοδος

Ανοίγει το συγκεκριμένο αρχείο στη δηλωμένη λειτουργία, με τον καθορισμένο τύπο πρόσβασης και την επιλογή κοινής χρήσης.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου προς άνοιγμα |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία με την οποία θα ανοίξει το αρχείο |
| access | [FileAccess](../../fileaccess/) | Ο ζητούμενος τύπος πρόσβασης |
| share | [FileShare](../../fileshare/) | Ο τύπος πρόσβασης που άλλα αντικείμενα [FileStream](../../filestream/) έχουν στο ανοιγμένο αρχείο |

### Τιμή Επιστροφής

Ένα αντικείμενο [FileStream](../../filestream/) που σχετίζεται με το ανοιγμένο αρχείο

## Δείτε επίσης

* Αρίθμηση [FileMode](../../filemode/)
* Αρίθμηση [FileAccess](../../fileaccess/)
* Αρίθμηση [FileShare](../../fileshare/)
* Ορισμός τύπου [FileStreamPtr](../../../system/filestreamptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [File](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)