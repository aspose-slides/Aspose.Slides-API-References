---
title: Create()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου ECDSA.
type: docs
weight: 131
url: /el/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() μέθοδος

Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Τιμή Επιστροφής

Αντικείμενο αλγόριθμου ECDSA.

## ECDsa::Create(const ECCurve\&) μέθοδος

Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου ECDSA με νεοδημιουργημένο κλειδί πάνω στην καθορισμένη καμπύλη.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Καμπύλη που θα χρησιμοποιηθεί για τη δημιουργία του κλειδιού. |

### Τιμή Επιστροφής

Αντικείμενο αλγόριθμου ECDSA.

## ECDsa::Create(const ECParameters\&) μέθοδος

Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου ECDSA χρησιμοποιώντας τις καθορισμένες παραμέτρους.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Παράμετροι που αντιπροσωπεύουν το κλειδί. |

### Τιμή Επιστροφής

Αντικείμενο αλγόριθμου ECDSA.

## ECDsa::Create(const String\&) μέθοδος

Δημιουργεί την καθορισμένη υλοποίηση αλγόριθμου ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Όνομα αλγόριθμου. |

### Τιμή Επιστροφής

Αντικείμενο αλγόριθμου ECDSA.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ECDsa](../)
* Κλάση [String](../../../system/string/)
* Δομή [ECCurve](../../eccurve/)
* Δομή [ECParameters](../../ecparameters/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)