---
title: GetDirectories()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναζητά τους φακέλους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης, είτε στον καθορισμένο φάκελο, είτε σε ολόκληρο το δέντρο φακέλων που αρχίζει από τον καθορισμένο φάκελο.
type: docs
weight: 66
url: /el/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) μέθοδος


Αναζητά τους φακέλους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης, είτε στον καθορισμένο φάκελο, είτε σε ολόκληρο το δέντρο φακέλων που αρχίζει από τον καθορισμένο φάκελο.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Πλήρης ή σχετική διαδρομή του φακέλου στον οποίο θα γίνει η αναζήτηση |
| searchPattern | const [String](../../../system/string/)\& | Το πρότυπο ονόματος των φακέλων που θα αναζητηθούν |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει αν η αναζήτηση πρέπει να εκτελεστεί μόνο στον καθορισμένο φάκελο ή σε ολόκληρο το δέντρο φακέλων που αρχίζει από τον καθορισμένο φάκελο |

### Τιμή Επιστροφής

Ένας πίνακας πλήρων διαδρομών των εντοπισμένων φακέλων των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε Επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Directory](../)
* Ονομαχώρος [System::IO](../../)
* Library [Aspose.Slides](../../../)