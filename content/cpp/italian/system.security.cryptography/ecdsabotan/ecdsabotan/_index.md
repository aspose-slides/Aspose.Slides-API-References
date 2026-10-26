---
title: ECDsaBotan()
second_title: Riferimento API Aspose.Slides per C++
description: Costruttore. Usa i parametri predefiniti.
type: docs
weight: 1
url: /it/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() costruttore


Costruttore. Usa i parametri predefiniti.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parametri dell'algoritmo. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curva usata per creare la coppia di chiavi pubblica/privata. |

## ECDsaBotan::ECDsaBotan(int32_t) costruttore


Costruttore.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key_size | **int32_t** | Dimensione della chiave in bit. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Chiave pubblica Botan. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Chiave privata Botan. |

## Vedi anche

* Classe [ECDsaBotan](../)
* Struct [ECParameters](../../ecparameters/)
* Struct [ECCurve](../../eccurve/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)