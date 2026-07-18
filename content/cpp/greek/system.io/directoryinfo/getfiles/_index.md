---
title: GetFiles()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει έναν πίνακα που περιέχει κοινές pointers προς αντικείμενα FileInfo που αντιπροσωπεύουν όλους τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 157
url: /el/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method

Επιστρέφει έναν πίνακα που περιέχει κοινές pointers προς αντικείμενα [FileInfo](../../fileinfo/) που αντιπροσωπεύουν όλους τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) method

Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το μοτίβο ονόματος των αρχείων προς αναζήτηση |

### Return Value

Ένας πίνακας κοινών pointers προς αντικείμενα [FileInfo](../../fileinfo/) που αντιπροσωπεύουν τα ευρεθέντα αρχεία των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) method

Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο, είτε σε ολόκληρο το δέντρο καταλόγου που ριζώνεται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το μοτίβο ονόματος των αρχείων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει εάν η αναζήτηση πρέπει να πραγματοποιηθεί μόνο στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο ή σε ολόκληρο το δέντρο καταλόγου που ριζώνεται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο |

### Return Value

Ένας πίνακας κοινών pointers προς αντικείμενα [FileInfo](../../fileinfo/) που αντιπροσωπεύουν τα ευρεθέντα αρχεία των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)