---
title: ECDsaBotan()
second_title: Aspose.Slides pro C++ API Reference
description: Konstruktor. Používá výchozí parametry.
type: docs
weight: 1
url: /cs/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() konstruktor

Konstruktor. Používá výchozí parametry.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parametry algoritmu. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Křivka použitá k vytvoření páru veřejného/soukromého klíče. |

## ECDsaBotan::ECDsaBotan(int32_t) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key_size | **int32_t** | Velikost klíče v bitech. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Veřejný klíč Botan. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Soukromý klíč Botan. |

## Viz také

* Třída [ECDsaBotan](../)
* Struktura [ECParameters](../../ecparameters/)
* Struktura [ECCurve](../../eccurve/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)