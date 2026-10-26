---
title: EnumerateFiles()
second_title: Αναφορά API Aspose.Slides για C++
description: Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο φάκελο είτε σε όλο το δέντρο φακέλων που αρχίζει από τον καθορισμένο φάκελο.
type: docs
weight: 40
url: /el/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) μέθοδος

Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο φάκελο είτε σε όλο το δέντρο καταλόγων που αρχίζει από τον καθορισμένο φάκελο.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Πλήρης ή σχετικό μονοπάτι προς τον φάκελο όπου θα γίνει η αναζήτηση |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των αρχείων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει αν η αναζήτηση πρέπει να γίνει μόνο στον καθορισμένο φάκελο ή σε όλο το δέντρο καταλόγων που αρχίζει από τον καθορισμένο φάκελο |

### Τιμή Επιστροφής

Η συλλογή με δυνατότητα επανάληψης από πλήρη μονοπάτια των αρχείων που βρέθηκαν και των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Directory](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)