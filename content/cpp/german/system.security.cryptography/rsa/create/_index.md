---
title: Create()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt die Standardimplementierung des RSA-Algorithmus.
type: docs
weight: 183
url: /de/system.security.cryptography/rsa/create/
---
## RSA::Create() Methode

Erstellt die Standardimplementierung des [RSA](../)-Algorithmus.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) Methode

Erstellt die Standardimplementierung des [RSA](../)-Algorithmus.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Muss \"System.Security.Cryptography.RSACryptoServiceProvider\" sein. |

## RSA::Create(int32_t) Methode

Erstellt die Standardimplementierung des [RSA](../)-Algorithmus mit angegebener Schlüssellänge.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Die Schlüssellänge in Bits. |

## RSA::Create(const RSAParameters\&) Methode

Erstellt die Standardimplementierung des [RSA](../)-Algorithmus mit angegebenen Parametern.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Die Parameter für den [RSA](../)-Algorithmus. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSA](../)
* Klasse [String](../../../system/string/)
* Struktur [RSAParameters](../../rsaparameters/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)