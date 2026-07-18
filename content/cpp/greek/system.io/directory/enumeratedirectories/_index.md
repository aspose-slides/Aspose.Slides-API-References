---
title: EnumerateDirectories()
second_title: Αναφορά API Aspose.Slides για C++
description: Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε ολόκληρο το δέντρο καταλόγων που ρίζεται στον καθορισμένο κατάλογο.
type: docs
weight: 27
url: /el/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) μέθοδος

Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε ολόκληρο το δέντρο καταλόγων που ρίζεται στον καθορισμένο κατάλογο.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Πλήρης ή σχετικό μονοπάτι προς τον κατάλογο προς αναζήτηση |
| searchPattern | const [String](../../../system/string/)& | Το μοτίβο ονόματος των καταλόγων προς αναζήτηση |
| searchOption | [SearchOption](../../searchoption/) | Καθορίζει εάν η αναζήτηση πρέπει να εκτελεστεί μόνο στον καθορισμένο κατάλογο ή σε ολόκληρο το δέντρο καταλόγων που ρίζεται στον καθορισμένο κατάλογο |

## Τιμή Επιστροφής

Η συλλογή με δυνατότητα αρίθμησης των πλήρων διαδρομών των ευρεθέντων καταλόγων των οποίων τα ονόματα ταιριάζουν με **searchPattern**

## Δείτε επίσης

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Directory](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)