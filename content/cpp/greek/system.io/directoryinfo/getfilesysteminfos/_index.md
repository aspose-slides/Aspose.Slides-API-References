---
title: GetFileSystemInfos()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει έναν πίνακα που περιέχει κοινά δείκτες σε αντικείμενα FileSystemInfo που αντιπροσωπεύουν όλα τα αρχεία και τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 170
url: /el/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() μέθοδος

Επιστρέφει έναν πίνακα που περιέχει κοινά δείκτες σε αντικείμενα [FileSystemInfo](../../filesysteminfo/) που αντιπροσωπεύουν όλα τα αρχεία και τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) μέθοδος

Αναζητά τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων και των καταλόγων που θα αναζητηθούν |

### Τιμή Επιστροφής

Ένας πίνακας κοινών δεικτών σε αντικείμενα [FileSystemInfo](../../filesysteminfo/) που αντιπροσωπεύουν τα ευρεθέντα αρχεία και καταλόγους των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) μέθοδος

Αναζητά τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο είτε στο πλήρες δένδρο καταλόγων που έχει ως ρίζα τον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων και των καταλόγων που θα αναζητηθούν |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει εάν η αναζήτηση πρέπει να γίνει μόνο στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο ή σε όλο το δένδρο καταλόγων που έχει ως ρίζα τον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο |

### Τιμή Επιστροφής

Ένας πίνακας κοινών δεικτών σε αντικείμενα [FileSystemInfo](../../filesysteminfo/) που αντιπροσωπεύουν τα ευρεθέντα αρχεία και καταλόγους των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)