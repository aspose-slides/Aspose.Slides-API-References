---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί FileStream με την καθορισμένη διαδρομή και τρόπο δημιουργίας.
type: docs
weight: 14
url: /el/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) μέθοδος

Δημιουργεί FileStream με την καθορισμένη διαδρομή και τρόπο δημιουργίας.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |

### Τιμή Επιστροφής

Περιτύλιγμα ροής για τη διασύνδεση COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) μέθοδος

Δημιουργεί FileStream με την καθορισμένη διαδρομή, τρόπο δημιουργίας και δικαίωμα ανάγνωσης/εγγραφής.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | File access [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Τιμή Επιστροφής

Περιτύλιγμα ροής για τη διασύνδεση COM [IStreamWrapper](../../istreamwrapper/)

## Δείτε επίσης

* Αρίθμηση [FileMode](../../../system.io/filemode/)
* Αρίθμηση [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IStreamWrapper](../../istreamwrapper/)
* Κλάση [String](../../../system/string/)
* Κλάση [IStreamWrapperFactory](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)