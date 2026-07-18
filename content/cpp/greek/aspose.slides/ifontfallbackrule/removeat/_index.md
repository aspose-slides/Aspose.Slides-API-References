---
title: RemoveAt()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καταργεί τη γραμματοσειρά FallBack στη συγκεκριμένη θέση της λίστας.
type: docs
weight: 92
url: /el/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) μέθοδος


Καταργεί τη γραμματοσειρά FallBack στη συγκεκριμένη θέση της λίστας.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης της γραμματοσειράς που θα αφαιρεθεί. |
## Σχόλια



```cpp
// Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Αφαίρεση του Tahoma από τη λίστα
newRule->RemoveAt(2);
```


## Δείτε επίσης

* Κλάση [IFontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)