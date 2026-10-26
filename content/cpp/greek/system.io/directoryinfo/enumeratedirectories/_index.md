---
title: EnumerateDirectories()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει συλλογή με δυνατότητα επανάληψης που περιέχει όλους τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 105
url: /el/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() μέθοδος


Επιστρέφει συλλογή με δυνατότητα επανάληψης που περιέχει όλους τους καταλόγους που βρίσκονται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) μέθοδος


Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το μοτίβο ονόματος των καταλόγων που θα αναζητηθούν |

### Τιμή Επιστροφής

Η συλλογή με δυνατότητα επανάληψης από κοινές δείκτες προς αντικείμενα [DirectoryInfo](../) που αντιπροσωπεύουν τους βρεθέντες καταλόγους των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) μέθοδος


Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο είτε σε όλο το δένδρο καταλόγων που ριζώνεται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Το μοτίβο ονόματος των καταλόγων που θα αναζητηθούν |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει αν η αναζήτηση πρέπει να εκτελεστεί μόνο στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο ή σε όλο το δένδρο καταλόγων που ριζώνεται στον κατάλογο που αντιπροσωπεύεται από το τρέχον αντικείμενο |

### Τιμή Επιστροφής

Η συλλογή με δυνατότητα επανάληψης από κοινές δείκτες προς αντικείμενα [DirectoryInfo](../) που αντιπροσωπεύουν τους βρεθέντες καταλόγους των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)