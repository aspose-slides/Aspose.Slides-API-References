---
title: RemoveScriptFont()
second_title: Aspose.Slides για αναφορά API C++
description: Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος.
type: docs
weight: 118
url: /el/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) μέθοδος

Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Ο κωδικός BCP-47 του σεναρίου του οποίου η ρύθμιση γραμματοσειράς πρέπει να αφαιρεθεί. |

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει πώς να αφαιρεθεί η αντιστοίχιση γραμματοσειράς για το εβραϊκό script:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [Fonts](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)