---
title: Open()
second_title: Αναφορά API του Aspose.Slides για C++
description: Ανοίγει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στη συγκεκριμένη λειτουργία για ανάγνωση και εγγραφή χωρίς κοινή χρήση.
type: docs
weight: 183
url: /el/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) μέθοδος

Ανοίγει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στη συγκεκριμένη λειτουργία για ανάγνωση και εγγραφή χωρίς κοινή χρήση.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία στην οποία θα ανοιχτεί το αρχείο |

### Τιμή επιστροφής

Ένα αντικείμενο [FileStream](../../filestream/) συνδεδεμένο με το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο

## FileInfo::Open(FileMode, FileAccess) μέθοδος

Ανοίγει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη λειτουργία, με τον καθορισμένο τύπο πρόσβασης και χωρίς κοινή χρήση.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία στην οποία θα ανοιχτεί το αρχείο |
| access | [FileAccess](../../fileaccess/) | Ο ζητούμενος τύπος πρόσβασης |

### Τιμή επιστροφής

Ένα αντικείμενο [FileStream](../../filestream/) συνδεδεμένο με το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο

## FileInfo::Open(FileMode, FileAccess, FileShare) μέθοδος

Ανοίγει το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο στην καθορισμένη λειτουργία, με τον καθορισμένο τύπο πρόσβασης και επιλογή κοινής χρήσης.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία στην οποία θα ανοιχτεί το αρχείο |
| access | [FileAccess](../../fileaccess/) | Ο ζητούμενος τύπος πρόσβασης |
| share | [FileShare](../../fileshare/) | Ο τύπος πρόσβασης που άλλα αντικείμενα [FileStream](../../filestream/) έχουν στο ανοιγμένο αρχείο |

### Τιμή επιστροφής

Ένα αντικείμενο [FileStream](../../filestream/) συνδεδεμένο με το αρχείο που αντιπροσωπεύεται από το τρέχον αντικείμενο

## Δείτε επίσης

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)