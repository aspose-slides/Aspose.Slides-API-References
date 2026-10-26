---
title: IsMatch()
second_title: Αναφορά API για C++ του Aspose.Slides
description: Ταιριάζει τη regex με τη συμβολοσειρά.
type: docs
weight: 53
url: /el/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) μέθοδος

Ταιριάζει τη regex με τη συμβολοσειρά.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά-στόχος. |
| startat | int | Αρχικός δείκτης. |

### Τιμή επιστροφής

Αληθές εάν η συμβολοσειρά ταιριάζει με τη regex, ψευδές διαφορετικά.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) μέθοδος

Ελέγχει εάν η συμβολοσειρά ταιριάζει με το μοτίβο.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | Μοτίβο regex. |
| options | [RegexOptions](../../regexoptions/) | Επιλογές αντιστοίχισης. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Χρονικό όριο. |
| startat | int | [Match](../../match/) αρχική θέση. |

### Τιμή επιστροφής

Αληθές εάν βρεθεί ταύτο, ψευδές διαφορετικά.

## Δείτε επίσης

* Enum [RegexOptions](../../regexoptions/)
* Κλάση [String](../../../system/string/)
* Κλάση [Regex](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Text::RegularExpressions](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)