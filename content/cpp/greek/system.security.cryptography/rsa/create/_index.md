---
title: Create()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί την προεπιλεγμένη υλοποίηση αλγορίθμου RSA.
type: docs
weight: 183
url: /el/system.security.cryptography/rsa/create/
---
## RSA::Create() μέθοδος


Δημιουργεί την προεπιλεγμένη υλοποίηση αλγορίθμου [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) μέθοδος


Δημιουργεί την προεπιλεγμένη υλοποίηση αλγορίθμου [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Πρέπει να είναι "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) μέθοδος


Δημιουργεί την προεπιλεγμένη υλοποίηση αλγορίθμου [RSA](../) με καθορισμένο μέγεθος κλειδιού.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Το μέγεθος του κλειδιού, σε bits. |

## RSA::Create(const RSAParameters\&) μέθοδος


Δημιουργεί την προεπιλεγμένη υλοποίηση αλγορίθμου [RSA](../) με καθορισμένες παραμέτρους.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Οι παράμετροι για τον αλγόριθμο [RSA](../). |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [RSA](../)
* Κλάση [String](../../../system/string/)
* Δομή [RSAParameters](../../rsaparameters/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)