---
title: Match()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ταιριάζει regex με τη συμβολοσειρά.
type: docs
weight: 66
url: /el/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) μέθοδος

Ταιριάζει το regex με τη συμβολοσειρά.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά-στόχος. |

### Τιμή Επιστροφής

[Match](../../match/) τιμή που περιέχει την κατάσταση αντιστοίχισης και τις υποαντιστοιχίες.

## Regex::Match(const String\&, int, int) μέθοδος

Ταιριάζει το regex με τη συμβολοσειρά.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά-στόχος. |
| startat | int | Αρχικός δείκτης. |
| length | int | Αριθμός χαρακτήρων προς εξέταση (0 για όλη τη συμβολοσειρά). |

### Τιμή Επιστροφής

[Match](../../match/) τιμή που περιέχει την κατάσταση αντιστοίχισης και τις υποαντιστοιχίες.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) μέθοδος

Ταιριάζει τη συμβολοσειρά και το μοτίβο.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | Μοτίβο regexp. |
| options | [RegexOptions](../../regexoptions/) | Επιλογές αντιστοίχισης. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Χρονικό όριο. |
| startat | int | [Match](../../match/) αρχική θέση. |
| length | int | Αριθμός χαρακτήρων προς εξέταση (0 απενεργοποιεί το όριο). |

### Τιμή Επιστροφής

Βρέθηκε η πρώτη αντιστοιχία.

## Δείτε επίσης

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)