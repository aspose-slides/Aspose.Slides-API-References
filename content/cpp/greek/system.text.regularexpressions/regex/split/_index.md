---
title: Split()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαιρεί τη συμβολοσειρά με βάση τα ταιριάσματα της κανονικής έκφρασης.
type: docs
weight: 105
url: /el/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) μέθοδος

Διαιρεί τη συμβολοσειρά με βάση τα ταιριάσματα της κανονικής έκφρασης.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) για διαχωρισμό. |

### Τιμή Επιστροφής

[Array](../../../system/array/) των υποσυμβολοσειρών μεταξύ των αντιστοιχίσεων.

## Regex::Split(const String\&, int) μέθοδος

Διαιρεί τη συμβολοσειρά με βάση τα ταιριάσματα της κανονικής έκφρασης.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) για διαχωρισμό. |
| count | int | Όριο αριθμού υποσυμβολοσειρών. |

### Τιμή Επιστροφής

[Array](../../../system/array/) των υποσυμβολοσειρών μεταξύ των αντιστοιχίσεων.

## Regex::Split(const String\&, int, int) μέθοδος

Διαιρεί μια συμβολοσειρά εισόδου έναν καθορισμένο μέγιστο αριθμό φορών σε έναν πίνακα υποσυμβολοσειρών, στις θέσεις που ορίζονται από μια κανονική έκφραση που έχει καθοριστεί στο κατασκευαστή [Regex](../). Η αναζήτηση του προτύπου της κανονικής έκφρασης ξεκινά σε μια καθορισμένη θέση χαρακτήρα στη συμβολοσειρά εισόδου.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Η συμβολοσειρά προς διαχωρισμό. |
| count | int | Ο μέγιστος αριθμός φορών που μπορεί να γίνει ο διαχωρισμός. |
| startat | int | Η θέση χαρακτήρα στη συμβολοσειρά εισόδου όπου η αναζήτηση θα ξεκινήσει. |

### Τιμή Επιστροφής

Ένας πίνακας συμβολοσειρών.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) μέθοδος

Διαιρεί τη συμβολοσειρά με βάση την κανονική έκφραση.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | Πρότυπο κανονικής έκφρασης. |
| options | [RegexOptions](../../regexoptions/) | Επιλογές αντιστοίχισης. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Χρονικό όριο. |

### Τιμή Επιστροφής

[Array](../../../system/array/) των συμβολοσειρών μεταξύ των αντιστοιχίσεων.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) μέθοδος

Διαιρεί τη συμβολοσειρά με βάση την κανονική έκφραση.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | Πρότυπο κανονικής έκφρασης. |
| count | int | [Match](../../match/) όριο αριθμού. |
| options | [RegexOptions](../../regexoptions/) | Επιλογές αντιστοίχισης. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Χρονικό όριο. |

### Τιμή Επιστροφής

[Array](../../../system/array/) των συμβολοσειρών μεταξύ των αντιστοιχίσεων.

## Δείτε επίσης

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Regex](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)