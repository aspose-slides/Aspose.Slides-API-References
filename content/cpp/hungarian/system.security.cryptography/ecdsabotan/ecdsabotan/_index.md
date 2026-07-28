---
title: ECDsaBotan()
second_title: Aspose.Slides for C++ API Referencia
description: Konstruktor. Alapértelmezett paramétereket használ.
type: docs
weight: 1
url: /hu/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() konstruktor


Konstruktor. Alapértelmezett paramétereket használ.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Algoritmus paraméterek. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | A nyilvános/privát kulcspár létrehozásához használt görbe. |

## ECDsaBotan::ECDsaBotan(int32_t) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key_size | **int32_t** | Kulcsméret bitekben. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan nyilvános kulcs. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan privát kulcs. |

## Lásd még

* Osztály [ECDsaBotan](../)
* Struktúra [ECParameters](../../ecparameters/)
* Struktúra [ECCurve](../../eccurve/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)