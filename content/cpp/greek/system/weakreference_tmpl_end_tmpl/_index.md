---
title: WeakReference<>
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει μια αδύναμη αναφορά, η οποία αναφέρεται σε ένα αντικείμενο ενώ εξακολουθεί να επιτρέπει τη διαγραφή του αντικειμένου.
type: docs
weight: 1496
url: /el/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> κλάση

Αντιπροσωπεύει μια αδύναμη αναφορά, η οποία αναφέρεται σε ένα αντικείμενο ενώ εξακολουθεί να επιτρέπει τη διαγραφή του αντικειμένου.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Λαμβάνει ένδειξη εάν το αντικείμενο στο οποίο κάνει αναφορά το τρέχον WeakReference αντικείμενο έχει διαγραφεί. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Λαμβάνει το αντικείμενο (τον στόχο) στο οποίο κάνει αναφορά το τρέχον WeakReference αντικείμενο. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Ορίζει το αντικείμενο (τον στόχο) στο οποίο κάνει αναφορά το τρέχον WeakReference αντικείμενο. |
|  [WeakReference](./weakreference/)() | Κατασκευαστής προεπιλογής. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Κατασκευαστής από nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WeakReference, που κάνει αναφορά στο καθορισμένο αντικείμενο. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WeakReference, που κάνει αναφορά στο καθορισμένο αντικείμενο. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)