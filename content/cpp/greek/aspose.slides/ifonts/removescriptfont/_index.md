---
title: RemoveScriptFont()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καταργεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος.
type: docs
weight: 118
url: /el/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) μέθοδος

Καταργεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Ο κώδικας script BCP-47 του οποίου η ρύθμιση γραμματοσειράς πρέπει να καταργηθεί. |
## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει πώς να καταργήσετε την αντιστοίχιση γραμματοσειράς για το script Hebrew:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IFonts](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)