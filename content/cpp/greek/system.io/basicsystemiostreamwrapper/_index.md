---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αναπαριστά ένα περιτύλιγμα τύπου std::iostream που χρησιμοποιεί το BasicSystemIOStreamBuf ως εσωτερική ενδιάμεση μνήμη."
type: docs
weight: 53
url: /el/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper κλάση

Αναπαριστά ένα περιτύλιγμα παρόμοιο με std::iostream που χρησιμοποιεί το [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) ως εσωτερική ενδιάμεση μνήμη.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Χρησιμοποιείται στον κατασκευαστή μετακίνησης και στον τελεστή ανάθεσης μετακίνησης για την επαναφορά των δεικτών και την κλήση του [swap()](./swap/). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Δημιουργεί ένα νέο στιγμιότυπο του [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Κατασκευαστής αντιγραφής. Διαγραμμένος. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Κατασκευαστής μετακίνησης. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Τελεστής ανάθεσης αντιγραφής. Διαγραμμένος. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Κλήση για ανταλλαγή του *this και του **right**, εφόσον δεν είναι ίσα. |

## Ορισμοί τύπου

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Δείτε επίσης

* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)