---
title: UriComponents
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναπαριστά τα στοιχεία URI.
type: docs
weight: 3212
url: /el/system/uricomponents/
---
## UriComponents enum

Αναπαριστά τα στοιχεία URI.

```cpp
enum class UriComponents
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Scheme | 1 | Τα δεδομένα Scheme. |
| UserInfo | 2 | Τα δεδομένα UserInfo. |
| Host | 4 | Τα δεδομένα Host. |
| Port | 8 | Τα δεδομένα Port. |
| SchemeAndServer | n/a | Τα δεδομένα Scheme, Host και Port. |
| Path | 16 | Τα δεδομένα LocalPath. |
| Query | 32 | Τα δεδομένα Query. |
| PathAndQuery | n/a | Τα δεδομένα LocalPath και Query. |
| HttpRequestUrl | n/a | Τα δεδομένα Scheme, Host, Port, Query και LocalPath. |
| Fragment | 64 | Τα δεδομένα Fragment. |
| AbsoluteUri | n/a | Τα δεδομένα Scheme, Host, Port, Quer, LocalPath και Fragment. |
| StrongPort | 128 | Τα δεδομένα Port· εάν τα δεδομένα Port δεν είναι παρόντα στο [Uri](../uri/) και μια προεπιλεγμένη θύρα έχει εκχωρηθεί στο Scheme, επιστρέφεται η προεπιλεγμένη θύρα· εάν δεν υπάρχει προεπιλεγμένη θύρα, επιστρέφεται -1. |
| HostAndPort | n/a | Τα δεδομένα Host και Port· εάν τα δεδομένα Port δεν είναι παρόντα στο [Uri](../uri/) και μια προεπιλεγμένη θύρα έχει εκχωρηθεί στο Scheme, επιστρέφεται η προεπιλεγμένη θύρα· εάν δεν υπάρχει προεπιλεγμένη θύρα, επιστρέφεται -1. |
| StrongAuthority | n/a | Τα δεδομένα UserInfo, Host και Port· εάν δεν υπάρχουν δεδομένα Port στο [Uri](../uri/) και μια προεπιλεγμένη θύρα έχει εκχωρηθεί στο Scheme, επιστρέφεται η προεπιλεγμένη θύρα· εάν δεν υπάρχει προεπιλεγμένη θύρα, επιστρέφεται -1. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Καθορίζει ότι το διαχωριστικό πρέπει να συμπεριληφθεί. |
| SerializationInfoString | n/a | Το πλήρες [Uri](../uri/) πλαίσιο που απαιτείται για τους Serializers του [Uri](../uri/). Το πλαίσιο περιλαμβάνει το IPv6 scope. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)