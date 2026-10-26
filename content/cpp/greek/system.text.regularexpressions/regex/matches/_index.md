---
title: Matches()
second_title: Αναφορά API Aspose.Slides για C++
description: Ανακτά όλες τις αντιστοιχίσεις του regex στη δεδομένη συμβολοσειρά με επαναλαμβανόμενη αντιστοίχιση.
type: docs
weight: 79
url: /el/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) μέθοδος

Ανακτά όλες τις αντιστοιχίσεις του regex στη δεδομένη συμβολοσειρά με επαναλαμβανόμενη αντιστοίχιση.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| startat | int | Δείκτης έναρξης αντιστοίχισης. |

### Τιμή Επιστροφής

Συλλογή όλων των ευρεθέντων αντιστοιχίσεων.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) μέθοδος

Ανακτά όλες τις αντιστοιχίσεις μεταξύ συμβολοσειράς και προτύπου.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | Πρότυπο κανονικής έκφρασης. |
| options | [RegexOptions](../../regexoptions/) | Επιλογές αντιστοίχισης. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Χρονικό όριο. |
| startat | int | [Match](../../match/) αρχική θέση. |
| length | int | Αριθμός χαρακτήρων προς εξέταση (0 απενεργοποιεί το όριο). |

### Τιμή Επιστροφής

Όλες οι αντιστοιχίσεις που βρέθηκαν με επαναλαμβανόμενη αντιστοίχιση.

## Δείτε επίσης

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)