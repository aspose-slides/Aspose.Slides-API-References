---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεί έναν buffer που περιβάλλει ροές τύπου System::IO::Stream και επιτρέπει τη χρήση τους ως εσωτερικό buffer ροών παρόμοιο με std::iostream."
type: docs
weight: 40
url: /el/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf κλάση

Αντιπροσωπεύει έναν buffer που περιβάλλει [System::IO::Stream](../stream/)-like streams και επιτρέπει τη χρήση τους ως εσωτερική buffer ροών παρόμοια με std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Χρησιμοποιείται στον κατασκευαστή μετακίνησης και στον τελεστή ανάθεσης μετακίνησης για την επαναφορά των δεικτών και την κλήση του [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Δημιουργεί μια νέα παρουσία του [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Δημιουργεί μια νέα παρουσία του [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Κατασκευαστής αντιγραφής. Διαγραμμένος. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Κατασκευαστής μετακίνησης. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Τελεστής αντιγραφής ανάθεσης. Διαγραμμένος. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Τελεστής μετακίνησης ανάθεσης. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Κλήση για ανταλλαγή *this και right, αν δεν είναι ίσα. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Καταστροφέας. |

## Ορισμοί τύπου

| Ορισμός | Περιγραφή |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Δείτε επίσης

* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)