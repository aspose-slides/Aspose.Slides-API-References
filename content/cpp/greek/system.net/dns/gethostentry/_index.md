---
title: GetHostEntry()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο παράδειγμα της κλάσης IPHostEntry χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP.
type: docs
weight: 79
url: /el/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) μέθοδος

Δημιουργεί ένα νέο παράδειγμα της κλάσης IPHostEntry χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Μια συμβολοσειρά που περιέχει ένα όνομα κεντρικού υπολογιστή ή διεύθυνση IP. |

### Τιμή Επιστροφής

Ένα νέο παράδειγμα της κλάσης IPHostEntry.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) μέθοδος

Δημιουργεί ένα νέο παράδειγμα της κλάσης IPHostEntry χρησιμοποιώντας τη συγκεκριμένη διεύθυνση IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Η διεύθυνση IP. |

### Τιμή Επιστροφής

Ένα νέο παράδειγμα της κλάσης IPHostEntry.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPHostEntry](../../iphostentry/)
* Κλάση [String](../../../system/string/)
* Κλάση [Dns](../)
* Κλάση [IPAddress](../../ipaddress/)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)