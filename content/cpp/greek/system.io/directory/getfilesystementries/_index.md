---
title: GetFileSystemEntries()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναζητεί τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που ριζώνεται στον καθορισμένο κατάλογο.
type: docs
weight: 92
url: /el/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) μέθοδος


Αναζητεί τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε ολόκληρο το δέντρο καταλόγων που ριζώνεται στον καθορισμένο κατάλογο.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Πλήρης ή σχετική διαδρομή προς τον κατάλογο όπου γίνεται η αναζήτηση |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων και καταλόγων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει εάν η αναζήτηση πρέπει να πραγματοποιηθεί μόνο στον καθορισμένο κατάλογο ή σε ολόκληρο το δέντρο καταλόγων που ριζώνεται στον καθορισμένο κατάλογο |

### Τιμή Επιστροφής

Ένας πίνακας με πλήρεις διαδρομές των ευρεθέντων αρχείων και καταλόγων των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Directory](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)