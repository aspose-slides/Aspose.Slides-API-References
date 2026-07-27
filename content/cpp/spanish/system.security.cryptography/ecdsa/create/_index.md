---
title: Create()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea la implementación predeterminada del algoritmo ECDSA.
type: docs
weight: 131
url: /es/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() método

Crea la implementación predeterminada del algoritmo ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Valor devuelto

Objeto de algoritmo ECDSA.

## ECDsa::Create(const ECCurve\&) método

Crea la implementación predeterminada del algoritmo ECDSA con una clave recién creada sobre la curva especificada.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curva a usar para la creación de la clave. |

### Valor devuelto

Objeto de algoritmo ECDSA.

## ECDsa::Create(const ECParameters\&) método

Crea la implementación predeterminada del algoritmo ECDSA usando los parámetros especificados.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parámetros que representan la clave. |

### Valor devuelto

Objeto de algoritmo ECDSA.

## ECDsa::Create(const String\&) método

Crea la implementación especificada del algoritmo ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Nombre del algoritmo. |

### Valor devuelto

Objeto de algoritmo ECDSA.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ECDsa](../)
* Clase [String](../../../system/string/)
* Struct [ECCurve](../../eccurve/)
* Struct [ECParameters](../../ecparameters/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)