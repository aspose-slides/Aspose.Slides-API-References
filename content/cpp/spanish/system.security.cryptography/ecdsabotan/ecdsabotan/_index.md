---
title: ECDsaBotan()
second_title: Referencia de la API de Aspose.Slides para C++
description: Constructor. Utiliza parámetros predeterminados.
type: docs
weight: 1
url: /es/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() constructor

Constructor. Utiliza parámetros predeterminados.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) constructor

Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parámetros del algoritmo. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) constructor

Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curva utilizada para crear el par de claves pública/privada. |

## ECDsaBotan::ECDsaBotan(int32_t) constructor

Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key_size | **int32_t** | Tamaño de clave en bits. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) constructor

Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Clave pública de Botan. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) constructor

Constructor.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Clave privada de Botan. |

## Ver también

* Clase [ECDsaBotan](../)
* Estructura [ECParameters](../../ecparameters/)
* Estructura [ECCurve](../../eccurve/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)