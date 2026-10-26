---
title: ECDsaBotan()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konstruktor. Używa domyślnych parametrów.
type: docs
weight: 1
url: /pl/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() konstruktor


Konstruktor. Używa domyślnych parametrów.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parametry algorytmu. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Krzywa używana do utworzenia pary kluczy publicznego/prywatnego. |

## ECDsaBotan::ECDsaBotan(int32_t) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key_size | **int32_t** | Rozmiar klucza w bitach. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Klucz publiczny Botan. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Klucz prywatny Botan. |

## Zobacz także

* Klasa [ECDsaBotan](../)
* Struktura [ECParameters](../../ecparameters/)
* Struktura [ECCurve](../../eccurve/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)