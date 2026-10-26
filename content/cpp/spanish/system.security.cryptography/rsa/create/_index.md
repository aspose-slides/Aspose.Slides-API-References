---
title: Create()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea la implementación predeterminada del algoritmo RSA.
type: docs
weight: 183
url: /es/system.security.cryptography/rsa/create/
---
## RSA::Create() método

Crea la implementación predeterminada del algoritmo [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) método

Crea la implementación predeterminada del algoritmo [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Debe ser \"System.Security.Cryptography.RSACryptoServiceProvider\". |

## RSA::Create(int32_t) método

Crea la implementación predeterminada del algoritmo [RSA](../) con el tamaño de clave especificado.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | El tamaño de la clave, en bits. |

## RSA::Create(const RSAParameters\&) método

Crea la implementación predeterminada del algoritmo [RSA](../) con los parámetros especificados.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Los parámetros para el algoritmo [RSA](../). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RSA](../)
* Clase [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)