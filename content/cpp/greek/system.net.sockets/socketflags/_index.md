---
title: SocketFlags
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει σταθερές τιμές για τα μηνύματα του socket.
type: docs
weight: 222
url: /el/system.net.sockets/socketflags/
---
## SocketFlags enum

Provides constant values for the socket messages.

```cpp
enum class SocketFlags
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | 0 | Δεν χρησιμοποιούνται σημαίες για αυτήν την κλήση. |
| OutOfBand | 1 | Τα out-of-band δεδομένα επεξεργάζονται. |
| Peek | 2 | Κοιτάξτε ένα εισερχόμενο μήνυμα. |
| DontRoute | 4 | Στείλτε ένα μήνυμα χωρίς χρήση πινάκων δρομολόγησης. |
| Truncated | 256 | Ένα μήνυμα είναι πολύ μεγάλο για να χωρέσει στο καθορισμένο buffer. Έχει περικοπεί. |
| ControlDataTruncated | 512 | Τα δεδομένα ελέγχου είναι μεγαλύτερα από 64 KB και δεν χωράνε στο εσωτερικό buffer. Έχουν περικοπεί. |
| Broadcast | 1024 | Ένα πακέτο εκπομπής. |
| Multicast | 2048 | Ένα πακέτο multicast. |
| Partial | 32768 | Ένα μήνυμα που έχει σταλθεί ή ληφθεί μερικώς. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Net::Sockets](../)
* Βιβλιοθήκη [Aspose.Slides](../../)