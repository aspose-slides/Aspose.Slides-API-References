---
title: Create()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea la implementación predeterminada del algoritmo DSA.
type: docs
weight: 105
url: /es/system.security.cryptography/dsa/create/
---
## DSA::Create() método

Crea la implementación predeterminada del algoritmo [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Valor devuelto

[DSA](../) objeto algoritmo.

## DSA::Create(const String\&) método

Crea la implementación predeterminada del algoritmo [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Debe ser "System.Security.Cryptography.DSACryptoServiceProvider". |

### Valor devuelto

[DSA](../) objeto algoritmo.

## DSA::Create(int32_t) método

Crea la implementación predeterminada del algoritmo [DSA](../) con el tamaño de clave especificado.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | El tamaño de la clave, en bits. |

## DSA::Create(const DSAParameters\&) método

Crea la implementación predeterminada del algoritmo [DSA](../) con los parámetros especificados.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Los parámetros del algoritmo [DSA](../). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [DSA](../)
* Clase [String](../../../system/string/)
* Estructura [DSAParameters](../../dsaparameters/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)