---
title: FieldAttributes
second_title: Aspose.Slides για C++ Αναφορά API
description: Χαρακτηριστικά πεδίου που αντανακλώνται.
type: docs
weight: 170
url: /el/system.reflection/fieldattributes/
---
## FieldAttributes enum

Χαρακτηριστικά πεδίου που αντανακλώνται.

```cpp
enum class FieldAttributes
```

### Values

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| FieldAccessMask | 7 | Μάσκα πρόσβασης μέλους. Χρησιμοποιήστε αυτή τη μάσκα για να ανακτήσετε πληροφορίες προσβασιμότητας. |
| PrivateScope | 0 | Μη αναφερόμενα μέλη. |
| Private | 1 | Ιδιωτικά μέλη. |
| FamANDAssem | 2 | Ιδιωτικά και με πεδίο συναρμολόγησης μέλη. |
| Assembly | 3 | Μέλη με πεδίο συναρμολόγησης. |
| Family | 4 | Μέλη προσβάσιμα από τον τύπο και τους υποτύπους. |
| FamORAssem | 5 | Μέλη προσβάσιμα από τον τύπο, τους υποτύπους και τη συναρμολόγηση. |
| Public | 6 | Μέλη προσβάσιμα από όλους. |
| Static | 16 | Static μέλη ως αντίθεση σε στιγμιότυπα μελών. |
| InitOnly | 32 | Const μέλη που μπορούν μόνο να αρχικοποιηθούν αλλά όχι να τροποποιηθούν. |
| Literal | 64 | Μέλη σταθερά κατά τη διάρκεια της μεταγλώττισης. |
| NotSerialized | 128 | Μέλη που δεν σειριακοποιούνται. |
| SpecialName | 512 | Ειδικό πεδίο με ένα από τα παρακάτω ονόματα. |
| PinvokeImpl | 8192 | Υλοποίηση που προωθείται μέσω interop. |
| ReservedMask | 38144 | Κρατημένες σημαίες μόνο για χρήση στο χρόνο εκτέλεσης. |
| RTSpecialName | 1024 | Το runtime πρέπει να ελέγξει την κωδικοποίηση του ονόματος. |
| HasFieldMarshal | 4096 | Παρουσιάζονται πληροφορίες διαμεταγωγής. |
| HasDefault | 32768 | Παρουσιάζεται προεπιλεγμένη τιμή. |
| HasFieldRVA | 256 | Παρουσιάζεται RVA. |

## See Also

* Namespace [System::Reflection](../)
* Library [Aspose.Slides](../../)