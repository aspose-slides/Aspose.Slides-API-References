---
title: GetFiles()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε ολόκληρο το δέντρο καταλόγων που ρίζεται στον καθορισμένο κατάλογο.
type: docs
weight: 79
url: /el/system.io/directory/getfiles/
---
## Directory::GetFiles(const String&, const String&, SearchOption) μέθοδος

Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που ρίζεται στον καθορισμένο κατάλογο.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Πλήρης ή σχετική διαδρομή προς τον κατάλογο όπου θα γίνει η αναζήτηση |
| searchPattern | const [String](../../../system/string/)\& | Το μοτίβο ονόματος των αρχείων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει αν η αναζήτηση πρέπει να εκτελεστεί μόνο στον καθορισμένο κατάλογο ή σε όλο το δέντρο καταλόγων που ρίζεται στον καθορισμένο κατάλογο |

### Τιμή επιστροφής

Ένα σύνολο από πλήρεις διαδρομές των αρχείων που βρέθηκαν και των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Directory](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)