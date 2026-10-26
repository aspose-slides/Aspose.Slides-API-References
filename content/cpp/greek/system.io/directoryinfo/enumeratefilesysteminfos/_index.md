---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει μια επαναληπτική συλλογή που περιέχει όλα τα αρχεία και τους καταλόγους που βρίσκονται στον φάκελο που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 131
url: /el/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() μέθοδος

Επιστρέφει συλλογή επαναληπτικού τύπου που περιέχει όλα τα αρχεία και τους καταλόγους που βρίσκονται στο φάκελο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) μέθοδος

Αναζητεί τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης στον φάκελο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων και των καταλόγων προς αναζήτηση |

### Τιμή Επιστροφής

Η συλλογή επαναληπτικού τύπου από κοινές δείκτες σε αντικείμενα [FileSystemInfo](../../filesysteminfo/) που αντιπροσωπεύουν τα ευρεθέντα αρχεία και καταλόγους των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) μέθοδος

Αναζητεί τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον φάκελο που αντιπροσωπεύεται από το τρέχον αντικείμενο είτε σε όλο το δένδρο καταλόγων που ρίζεται στον φάκελο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων και των καταλόγων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει αν η αναζήτηση πρέπει να εκτελεστεί μόνο στον φάκελο που αντιπροσωπεύεται από το τρέχον αντικείμενο ή σε όλο το δένδρο καταλόγων που ρίζεται σε αυτόν |

### Τιμή Επιστροφής

Η συλλογή επαναληπτικού τύπου από κοινές δείκτες σε αντικείμενα [FileSystemInfo](../../filesysteminfo/) που αντιπροσωπεύουν τα ευρεθέντα αρχεία και καταλόγους των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)