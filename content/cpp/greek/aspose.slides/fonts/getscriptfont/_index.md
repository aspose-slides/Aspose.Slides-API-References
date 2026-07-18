---
title: GetScriptFont()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει το όνομα γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης.
type: docs
weight: 92
url: /el/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) μέθοδος

Λαμβάνει το όνομα γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Ο κώδικας script BCP-47 (π.χ., "Latn", "Cyrl", "Jpan") που χρησιμοποιείται για την ταυτοποίηση ενός συστήματος γραφής. |

### Τιμή επιστροφής

Το όνομα της γραμματοσειράς που χρησιμοποιείται για το καθορισμένο script, ή **null** εάν το script δεν είναι ορισμένο.

## Σχόλια

Αυτό το παράδειγμα δείχνει πώς να ανακτήσετε τη γραμματοσειρά που έχει εκχωρηθεί στο κυριλλικό script στο θέμα της παρουσίασης. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [Fonts](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)