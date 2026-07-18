---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides για την Αναφορά API του C++
description: "Αναπαριστά ένα περιτύλιγμα τύπου std::ostream που χρησιμοποίησε το BasicSystemIOStreamBuf ως εσωτερική μνήμη."
type: docs
weight: 79
url: /el/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper κλάση

Αναπαριστά ένα περιτύλιγμα τύπου std::ostream που χρησιμοποιεί το [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) ως εσωτερική μνήμη.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Χρησιμοποιείται στον μετακινούμενο κατασκευαστή και στον μετακινούμενο τελεστή εκχώρησης για την επαναφορά δεικτών και την κλήση του [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Δημιουργεί ένα νέο στιγμιότυπο του [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Κατασκευαστής αντιγραφής. Διαγραμμένος. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Μετακινούμενος κατασκευαστής. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Τελεστής εκχώρησης αντιγραφής. Διαγραμμένος. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Τελεστής εκχώρησης μετακίνησης. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Κλήση για ανταλλαγή του *this και του **right**, εάν δεν είναι ίσα. |

## Τύποι

| Typedef | Περιγραφή |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Δείτε επίσης

* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)