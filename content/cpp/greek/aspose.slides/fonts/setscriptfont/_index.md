---
title: SetScriptFont()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναθέτει ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία καθορίζει πώς θα αποδοθεί το κείμενο αυτής της γραφής στην παρουσίαση.
type: docs
weight: 105
url: /el/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) μέθοδος

Αναθέτει ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία καθορίζει πώς θα αποδοθεί το κείμενο αυτής της γραφής στην παρουσίαση.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Ο κωδικός script BCP-47 (π.χ., "Arab", "Hebr", "Hans") που αναγνωρίζει το σύστημα γραφής. |
| fontName | [System::String](../../../system/string/) | Το όνομα της γραμματοσειράς που θα ανατεθεί στην καθορισμένη γραφή. |

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει πώς να ορίσετε τη γραμματοσειρά για την αραβική γραφή σε "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [Fonts](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)