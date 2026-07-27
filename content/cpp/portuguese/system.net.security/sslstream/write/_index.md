---
title: Write()
second_title: Aspose.Slides for C++ Referência da API
description: Escreve o array de bytes especificado no fluxo.
type: docs
weight: 404
url: /pt/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) método

Escreve o array de bytes especificado no fluxo.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes a ser escrito. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escreve o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem escritos |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser escrito começa |
| count | **int32_t** | O número de elementos no subintervalo a ser escrito |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) método

Escreve o array de bytes especificado no fluxo.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array de bytes a ser escrito. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escreve o subintervalo especificado de bytes do array de bytes especificado no fluxo.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array contendo os bytes a serem escritos |
| offset | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser escrito começa |
| count | **int32_t** | O número de elementos no subintervalo a ser escrito |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)