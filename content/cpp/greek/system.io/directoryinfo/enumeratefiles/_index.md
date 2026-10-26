---
title: EnumerateFiles()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει επαναλήψιμη συλλογή που περιέχει όλα τα αρχεία που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 118
url: /el/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() μέθοδος


Επιστρέφει μια επαναλήψιμη συλλογή που περιέχει όλα τα αρχεία που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) μέθοδος


Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων προς αναζήτηση |

### Τιμή επιστροφής

Η επαναλήψιμη συλλογή από κοινές δεικτοδείκτες σε αντικείμενα [FileInfo](../../fileinfo/) που αντιπροσωπεύουν τα βρεθέντα αρχεία των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) μέθοδος


Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο είτε σε όλο το δέντρο καταλόγων που ριζώνεται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει εάν η αναζήτηση πρέπει να γίνει μόνο στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο ή σε όλο το δέντρο καταλόγων που ριζώνεται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο |

### Τιμή επιστροφής

Η επαναλήψιμη συλλογή από κοινές δεικτοδείκτες σε αντικείμενα [FileInfo](../../fileinfo/) που αντιπροσωπεύουν τα βρεθέντα αρχεία των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)