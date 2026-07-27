---
title: ComputeHash()
second_title: Aspose.Slides for C++ Referencia de API
description: Calcula el hash del búfer.
type: docs
weight: 14
url: /es/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) método


Calcula el hash del búfer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Búfer de origen. |

### Valor devuelto

Valor hash calculado.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) método


Calcula el hash de una porción del búfer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Búfer de origen. |
| offset | int | Desplazamiento en el búfer de origen. |
| count | int | Número de bytes a usar del búfer de origen. |

### Valor devuelto

Valor hash calculado.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) método


Lee el flujo hasta el final y calcula el hash de los datos leídos.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Flujo del que leer los datos. |

### Valor devuelto

Valor hash calculado para todos los datos del flujo.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)