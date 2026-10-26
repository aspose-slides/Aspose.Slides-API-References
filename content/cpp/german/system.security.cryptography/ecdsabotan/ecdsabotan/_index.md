---
title: ECDsaBotan()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruktor. Verwendet Standardparameter.
type: docs
weight: 1
url: /de/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() Konstruktor


Konstruktor. Verwendet Standardparameter.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Algorithmus-Parameter. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Kurve, die zum Erzeugen des öffentlichen/privaten Schlüsselpaares verwendet wird. |

## ECDsaBotan::ECDsaBotan(int32_t) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key_size | **int32_t** | Schlüsselgröße in Bits. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan-öffentlicher Schlüssel. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan privater Schlüssel. |

## Siehe auch

* Klasse [ECDsaBotan](../)
* Struktur [ECParameters](../../ecparameters/)
* Struktur [ECCurve](../../eccurve/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)