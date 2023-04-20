---
title: ECDsaBotan()
second_title: Aspose.Slides for C++ API Reference
description: Constructor. Uses default parameters.
type: docs
weight: 1
url: /cpp/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() constructor


Constructor. Uses default parameters.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Algorithm parameters. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curve used to create the public/private key pair. |

## ECDsaBotan::ECDsaBotan(int32_t) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key_size | **int32_t** | Key size in bits. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan public key. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) constructor


Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan private key. |

## See Also

* Class [ECDsaBotan](../)
* Struct [ECParameters](../../ecparameters/)
* Struct [ECCurve](../../eccurve/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)