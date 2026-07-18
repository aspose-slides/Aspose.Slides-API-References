---
title: SetScriptFont()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναθέτει ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία ορίζει πώς θα αποτυπώνεται το κείμενο αυτής της γραφής στην παρουσίαση.
type: docs
weight: 105
url: /el/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) μέθοδος

Αναθέτει ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία ορίζει πώς θα αποτυπώνεται το κείμενο αυτής της γραφής στην παρουσίαση.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Ο κωδικός γραφής BCP-47 (π.χ., "Arab", "Hebr", "Hans") που προσδιορίζει το σύστημα γραφής. |
| fontName | [System::String](../../../system/string/) | Το όνομα της γραμματοσειράς που θα ανατεθεί στη συγκεκριμένη γραφή. |
## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει πώς να ορίσετε τη γραμματοσειρά για τη γραφή Αραβικά σε "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IFonts](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)