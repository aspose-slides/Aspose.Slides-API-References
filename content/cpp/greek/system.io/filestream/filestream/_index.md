---
title: FileStream()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί ένα νέο στιγμιότυπο της κλάσης FileStream και το αρχικοποιεί με τις καθορισμένες παραμέτρους.
type: docs
weight: 1
url: /el/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [FileStream](../) και το αρχικοποιεί με τις καθορισμένες παραμέτρους.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου που θα ανοίξει. |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία με την οποία θα ανοίξει το αρχείο. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [FileStream](../) και το αρχικοποιεί με τις καθορισμένες παραμέτρους.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου που θα ανοίξει. |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία με την οποία θα ανοίξει το αρχείο. |
| access | [FileAccess](../../fileaccess/) | Ο ζητούμενος τύπος πρόσβασης. |
| share | [FileShare](../../fileshare/) | Ο τύπος πρόσβασης που έχουν άλλα [FileStream](../) αντικείμενα στο ανοιγμένο αρχείο. |
| buffer_size | **int32_t** | Ο αριθμός των byte που αποθηκεύονται σε ενδιάμεση μνήμη κατά τις λειτουργίες ανάγνωσης και εγγραφής. |
| options | [FileOptions](../../fileoptions/) | Επιπλέον επιλογές. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [FileStream](../) και το αρχικοποιεί με τις καθορισμένες παραμέτρους.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου που θα ανοίξει. |
| mode | [FileMode](../../filemode/) | Καθορίζει τη λειτουργία με την οποία θα ανοίξει το αρχείο. |
| access | [FileAccess](../../fileaccess/) | Ο ζητούμενος τύπος πρόσβασης. |
| share | [FileShare](../../fileshare/) | Ο τύπος πρόσβασης που έχουν άλλα [FileStream](../) αντικείμενα στο ανοιγμένο αρχείο. |
| buffer_size | **int32_t** | Ο αριθμός των byte που αποθηκεύονται σε ενδιάμεση μνήμη κατά τις λειτουργίες ανάγνωσης και εγγραφής. |
| useAsync | **bool** | Καθορίζει αν θα χρησιμοποιηθεί ασύγχρονη I/O ή συγχρονισμένη I/O. |
## Παρατηρήσεις



Το υποκείμενο λειτουργικό σύστημα ενδέχεται να μην υποστηρίζει ασύγχρονη I/O. 

## FileStream::FileStream(const FileStream\&) κατασκευαστής




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Δείτε επίσης

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Κλάση [String](../../../system/string/)
* Κλάση [FileStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)