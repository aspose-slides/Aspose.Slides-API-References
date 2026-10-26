---
title: GetScriptFont()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει το όνομα της γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης.
type: docs
weight: 92
url: /el/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) μέθοδος


Λαμβάνει το όνομα της γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα παρουσίασης.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Ο κώδικας script BCP-47 (π.χ., "Latn", "Cyrl", "Jpan") που χρησιμοποιείται για την αναγνώριση ενός συστήματος γραφής. |

### Τιμή επιστροφής

Το όνομα της γραμματοσειράς που χρησιμοποιείται για το συγκεκριμένο script, ή **null** εάν το script δεν έχει οριστεί.
## Παρατηρήσεις



Αυτό το παράδειγμα δείχνει πώς να ανακτηθεί η γραμματοσειρά που έχει εκχωρηθεί στο κυριλλικό script στο θέμα παρουσίασης. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IFonts](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)