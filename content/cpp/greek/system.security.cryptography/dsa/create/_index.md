---
title: Create()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί προεπιλεγμένη υλοποίηση αλγορίθμου DSA.
type: docs
weight: 105
url: /el/system.security.cryptography/dsa/create/
---
## DSA::Create() μέθοδος

Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Τιμή Επιστροφής

[DSA](../) αντικείμενο αλγόριθμου.

## DSA::Create(const String\&) μέθοδος

Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Πρέπει να είναι "System.Security.Cryptography.DSACryptoServiceProvider". |

### Τιμή Επιστροφής

[DSA](../) αντικείμενο αλγόριθμου.

## DSA::Create(int32_t) μέθοδος

Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου [DSA](../) με καθορισμένο μέγεθος κλειδιού.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Το μέγεθος του κλειδιού, σε bits. |

## DSA::Create(const DSAParameters\&) μέθοδος

Δημιουργεί προεπιλεγμένη υλοποίηση αλγόριθμου [DSA](../) με καθορισμένες παραμέτρους.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Οι παράμετροι για τον αλγόριθμο [DSA](../). |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSA](../)
* Class [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)