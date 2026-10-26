---
title: Create()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt die Standardimplementierung des DSA-Algorithmus.
type: docs
weight: 105
url: /de/system.security.cryptography/dsa/create/
---
## DSA::Create() Methode

Erstellt die Standardimplementierung des [DSA](../)-Algorithmus.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Rückgabewert

[DSA](../) Algorithmus-Objekt.

## DSA::Create(const String\&) Methode

Erstellt die Standardimplementierung des [DSA](../)-Algorithmus.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Muss "System.Security.Cryptography.DSACryptoServiceProvider" sein. |

### Rückgabewert

[DSA](../) Algorithmus-Objekt.

## DSA::Create(int32_t) Methode

Erstellt die Standardimplementierung des [DSA](../)-Algorithmus mit angegebener Schlüssellänge.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Die Schlüssellänge, in Bits. |

## DSA::Create(const DSAParameters\&) Methode

Erstellt die Standardimplementierung des [DSA](../)-Algorithmus mit angegebenen Parametern.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Die Parameter für den [DSA](../)-Algorithmus. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [DSA](../)
* Klasse [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)