---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee datos del flujo.
type: docs
weight: 14
url: /es/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Lee datos del flujo.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer de datos de destino. |
| offset | **int32_t** | Desplazamiento en el buffer de destino. |
| count | **int32_t** | Número de bytes a leer. |

### Valor devuelto

Número de bytes leídos realmente.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lee datos del flujo.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Buffer de datos de destino. |
| offset | **int32_t** | Desplazamiento en el buffer de destino. |
| count | **int32_t** | Número de bytes a leer. |

### Valor devuelto

Número de bytes leídos realmente.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [CryptoStream](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)