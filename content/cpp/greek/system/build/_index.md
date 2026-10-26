---
title: Build()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργήστε ένα αντικείμενο με άμεση ιδιοκτησία.
type: docs
weight: 2263
url: /el/system/build/
---
## System::Build(Args\&&...) συνάρτηση


Δημιουργήστε ένα αντικείμενο με άμεση ιδιοκτησία.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος του αντικειμένου προς κατασκευή |
| Args | Τύποι ορισμάτων για την κατασκευή του αντικειμένου |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Ορίσματα προς προώθηση στον κατασκευαστή του αντικειμένου |

### Τιμή Επιστροφής

ObjectBuilder διαμορφωμένο για άμεση κατασκευή αντικειμένου
## Σχόλια



[Object](../object/) η κατασκευή πρέπει να ολοκληρωθεί με κλήση [Get()](../get/) 

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)