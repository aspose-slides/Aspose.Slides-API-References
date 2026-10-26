---
title: EnumerateFileSystemEntries()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναζητά τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε ολόκληρο το δέντρο καταλόγων που ριζώνει στον καθορισμένο κατάλογο.
type: docs
weight: 53
url: /el/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String&, const String&, SearchOption) μέθοδος

Αναζητά τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε ολόκληρο το δένδρο καταλόγου που ριζώνει στον καθορισμένο κατάλογο.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Πλήρης ή σχετική διαδρομή προς τον κατάλογο στο οποίο γίνεται η αναζήτηση |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων και καταλόγων για την αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει αν η αναζτηση πρέπει να εκτελεστεί μόνο στον καθορισμένο κατάλογο ή σε όλο το δένδρο καταλόγου που ρίζεται στον καθορισμένο κατάλογο |

### Τιμή Επιστροφής

Η συλλογή επαναλήψιμων πλήρων διαδρομών των ευρεθέντων αρχείων και καταλόγων των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)