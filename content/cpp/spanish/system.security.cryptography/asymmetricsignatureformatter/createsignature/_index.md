---
title: CreateSignature()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea la firma para los datos especificados.
type: docs
weight: 1
url: /es/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) método


Crea la firma para los datos especificados.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) para calcular el hash de. |

### Valor devuelto

Firma calculada en forma de matriz de bytes.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) método


Crea la firma para el valor de hash especificado.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algoritmo de hash a usar al crear la firma. |

### Valor devuelto

Firma calculada en forma de matriz de bytes.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [AsymmetricSignatureFormatter](../)
* Clase [HashAlgorithm](../../hashalgorithm/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)