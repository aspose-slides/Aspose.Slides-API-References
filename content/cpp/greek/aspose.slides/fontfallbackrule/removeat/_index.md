---
title: RemoveAt()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καταργεί τη γραμματοσειρά FallBack στον καθορισμένο δείκτη της λίστας.
type: docs
weight: 131
url: /el/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) μέθοδος

Καταργεί τη γραμματοσειρά FallBack στον καθορισμένο δείκτη της λίστας.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης της γραμματοσειράς προς αφαίρεση. |
## Παρατηρήσεις

```cpp
// Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Αφαιρεί το Tahoma από τη λίστα.
newRule->RemoveAt(2);
```

## Δείτε επίσης

* Κλάση [FontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)