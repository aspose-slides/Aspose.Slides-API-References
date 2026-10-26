---
title: GetBytes()
second_title: Referencia de API de Aspose.Slides para C++
description: Rellena los elementos del arreglo existente con bytes aleatorios.
type: docs
weight: 14
url: /es/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) método

Rellena los elementos del arreglo existente con bytes aleatorios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Arreglo de bytes para rellenar. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) método

Rellena el segmento del arreglo existente con bytes aleatorios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Arreglo de bytes para rellenar el segmento. |
| offset | int | Índice de inicio del segmento. |
| count | int | Tamaño del segmento. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) método

Rellena los elementos de la vista de arreglo existente con bytes aleatorios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Vista de arreglo de bytes para rellenar. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) método

Rellena el segmento de la vista de arreglo existente con bytes aleatorios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Vista de arreglo de bytes para rellenar el segmento. |
| offset | int | Índice de inicio del segmento. |
| count | int | Tamaño del segmento. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) método

Rellena los elementos del array de pila existente con bytes aleatorios.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Array de pila de bytes para rellenar. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) método

Rellena el segmento del array de pila existente con bytes aleatorios.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Array de pila de bytes para rellenar el segmento. |
| offset | int | Índice de inicio del segmento. |
| count | int | Tamaño del segmento. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [RandomNumberGenerator](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)