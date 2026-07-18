---
title: Replace()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντικαθιστά όλες τις αντιστοιχίες του regex σε συμβολοσειρά με τη συμβολοσειρά αντικατάστασης.
type: docs
weight: 92
url: /el/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες του regex σε συμβολοσειρά με τη συμβολοσειρά αντικατάστασης.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| replacement | const [String](../../../system/string/)\& | Συμβολοσειρά αντικατάστασης. |

### Τιμή επιστροφής

Συμβολοσειρά εισόδου με όλες τις αντιστοιχίες του regex αντικατεστημένες με τη συμβολοσειρά αντικατάστασης.

## Regex::Replace(const String\&, const char_t *) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες του regex σε συμβολοσειρά με τη συμβολοσειρά αντικατάστασης.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| replacement | const char_t * | Συμβολοσειρά αντικατάστασης. |

### Τιμή επιστροφής

Συμβολοσειρά εισόδου με όλες τις αντιστοιχίες του regex αντικατεστημένες με τη συμβολοσειρά αντικατάστασης.

## Regex::Replace(const String\&, const MatchEvaluator\&) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες σε συμβολοσειρά με αντικατάσταση που δημιουργείται από τον delegate.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate για τη δημιουργία συμβολοσειρών αντικατάστασης βάσει των αντιστοιχιών. |

### Τιμή επιστροφής

Συμβολοσειρές εισόδου με όλες τις αντιστοιχίες αντικατεστημένες.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες σε συμβολοσειρά με αντικατάσταση που δημιουργείται από τον delegate.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate για τη δημιουργία συμβολοσειρών αντικατάστασης βάσει των αντιστοιχιών. |
| count | int | Όριο αριθμού αντικαταστάσεων. |

### Τιμή επιστροφής

Συμβολοσειρές εισόδου με όλες τις αντιστοιχίες αντικατεστημένες.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες σε συμβολοσειρά με αντικατάσταση που δημιουργείται από τον delegate.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate για τη δημιουργία συμβολοσειρών αντικατάστασης βάσει των αντιστοιχιών. |
| count | int | Όριο αριθμού αντικαταστάσεων. |
| startat | int | Δείκτης στη συμβολοσειρά εισόδου από όπου αρχίζει η αντικατάσταση. |

### Τιμή επιστροφής

Συμβολοσειρές εισόδου με όλες τις αντιστοιχίες αντικατεστημένες.

## Regex::Replace(const String\&, const String\&, int) μέθοδος

Αντικαθιστά υποσυμβολοσειρές σε συμβολοσειρά. Δεν έχει υλοποιηθεί.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) μέθοδος

Αντικαθιστά υποσυμβολοσειρές σε συμβολοσειρά. Δεν έχει υλοποιηθεί.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες του regex σε συμβολοσειρά με τη συμβολοσειρά αντικατάστασης.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const char_t * | [Regex](../) πρότυπο. |
| replacement | const char_t * | Συμβολοσειρά αντικατάστασης. |

### Τιμή επιστροφής

Συμβολοσειρά εισόδου με όλες τις αντιστοιχίες του regex αντικατεστημένες με τη συμβολοσειρά αντικατάστασης.

## Regex::Replace(const String\&, const String\&, const char_t *) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες του regex σε συμβολοσειρά με τη συμβολοσειρά αντικατάστασης.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) πρότυπο. |
| replacement | const char_t * | Συμβολοσειρά αντικατάστασης. |

### Τιμή επιστροφής

Συμβολοσειρά εισόδου με όλες τις αντιστοιχίες του regex αντικατεστημένες με τη συμβολοσειρά αντικατάστασης.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες σε συμβολοσειρά με αντικατάσταση που δημιουργείται από delegate (στατική συνάρτηση).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) πρότυπο. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate για τη δημιουργία συμβολοσειρών αντικατάστασης βάσει των αντιστοιχιών. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) επιλογές. |

### Τιμή επιστροφής

Συμβολοσειρές εισόδου με όλες τις αντιστοιχίες αντικατεστημένες.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες του regex σε συμβολοσειρά με τη συμβολοσειρά αντικατάστασης.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) πρότυπο. |
| replacement | const [String](../../../system/string/)\& | Συμβολοσειρά αντικατάστασης. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) επιλογές. |

### Τιμή επιστροφής

Συμβολοσειρά εισόδου με όλες τις αντιστοιχίες του regex αντικατεστημένες με τη συμβολοσειρά αντικατάστασης.

## Regex::Replace(const String\&, const String\&, const String\&) μέθοδος

Αντικαθιστά τις αντιστοιχίες του regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | Πρότυπο Regexp. |
| replacement | const [String](../../../system/string/)\& | Συμβολοσειρά αντικατάστασης. |

### Τιμή επιστροφής

[String](../../../system/string/) με όλες τις αντιστοιχίες αντικατεστημένες.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) μέθοδος

Αντικαθιστά τις αντιστοιχίες του regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Συμβολοσειρά εισόδου. |
| pattern | const [String](../../../system/string/)\& | Πρότυπο Regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate για τη δημιουργία συμβολοσειράς αντικατάστασης για κάθε αντιστοιχία. |

### Τιμή επιστροφής

[String](../../../system/string/) με όλες τις αντιστοιχίες αντικατεστημένες.

## Δείτε επίσης

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)