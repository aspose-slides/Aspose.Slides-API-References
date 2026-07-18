---
title: GetDirectories()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Επιστρέφει έναν πίνακα που περιέχει shared pointers σε αντικείμενα DirectoryInfo που αντιπροσωπεύουν όλους τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 144
url: /el/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() μέθοδος


Επιστρέφει έναν πίνακα που περιέχει shared pointers σε αντικείμενα [DirectoryInfo](../) που αντιπροσωπεύουν όλους τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) μέθοδος


Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των καταλόγων προς αναζήτηση |

### Τιμή επιστροφής

Ένας πίνακας από shared pointers σε αντικείμενα [DirectoryInfo](../) που αντιπροσωπεύουν τους καταλόγους που βρέθηκαν και των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) μέθοδος


Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο είτε σε όλο το δένδρο καταλόγων που ριζώνει στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των καταλόγων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει αν η αναζήτηση πρέπει να εκτελεστεί μόνο στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο ή σε όλο το δένδρο καταλόγων που ριζώνει σε αυτόν |

### Τιμή επιστροφής

Ένας πίνακας από shared pointers σε αντικείμενα [DirectoryInfo](../) που αντιπροσωπεύουν τους καταλόγους που βρέθηκαν και των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)