---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides για την Αναφορά API του C++
description: "Αναπαριστά ένα wrapper τύπου std::istream που χρησιμοποιεί το BasicSystemIOStreamBuf ως εσωτερική προσωρινή μνήμη."
type: docs
weight: 66
url: /el/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper κλάση

Αντιπροσωπεύει ένα wrapper τύπου std::istream που χρησιμοποιεί το [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) ως εσωτερική προσωρινή μνήμη.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Χρησιμοποιείται στον κατασκευαστή μετακίνησης και στον τελεστή ανάθεσης μετακίνησης για την επαναφορά δεικτών και την κλήση του [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Δημιουργεί μια νέα παρουσία του [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Κατασκευαστής αντιγραφής. Διαγραμμένος. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Κατασκευαστής μετακίνησης. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Τελεστής ανάθεσης αντιγραφής. Διαγραμμένος. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Κλήση για ανταλλαγή του *this και του **right**, εάν δεν είναι ίσα. |

## Τύποι

| Δήλωση τύπου | Περιγραφή |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Δείτε επίσης

* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)