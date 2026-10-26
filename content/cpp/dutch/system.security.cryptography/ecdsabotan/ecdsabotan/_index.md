---
title: ECDsaBotan()
second_title: Aspose.Slides voor C++ API-referentie
description: Constructor. Gebruikt standaardparameters.
type: docs
weight: 1
url: /nl/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() constructor


Constructor. Gebruikt standaardparameters.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Algoritmeparameters. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curve die wordt gebruikt om het publieke/privé-sleutelpaar te maken. |

## ECDsaBotan::ECDsaBotan(int32_t) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key_size | **int32_t** | Sleutelgrootte in bits. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan openbare sleutel. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan privésleutel. |

## Zie ook

* Klasse [ECDsaBotan](../)
* Struct [ECParameters](../../ecparameters/)
* Struct [ECCurve](../../eccurve/)
* Naamruimte [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)