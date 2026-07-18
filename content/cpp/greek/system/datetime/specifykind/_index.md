---
title: SpecifyKind()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο αντικείμενο DateTime που αντιπροσωπεύει τον ίδιο αριθμό ticks με το καθορισμένο αντικείμενο DateTime και αντιπροσωπεύει τοπική ώρα, ώρα UTC ή καμία, όπως καθορίζεται από το όρισμα kind.
type: docs
weight: 833
url: /el/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) μέθοδος

Δημιουργεί ένα νέο [DateTime](../) αντικείμενο που αντιπροσωπεύει τον ίδιο αριθμό ticks όπως το καθορισμένο [DateTime](../) αντικείμενο και αντιπροσωπεύει τοπική ώρα, ώρα UTC ή καμία, όπως καθορίζεται από το όρισμα **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DateTime](../) | Το [DateTime](../) αντικείμενο από το οποίο θα αντιγραφεί ο αριθμός των ticks |
| kind | [DateTimeKind](../../datetimekind/) | Καθορίζει αν το νέο αντικείμενο πρέπει να αντιπροσωπεύει τοπική ώρα, ώρα UTC ή καμία |

### Τιμή Επιστροφής

Ένα νέο [DateTime](../) αντικείμενο που αντιπροσωπεύει τον ίδιο αριθμό ticks όπως το **value** και την τιμή DateTimeKind που καθορίζεται από το **kind**.

## Δείτε επίσης

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)