---
title: ComputeHash()
second_title: Referência da API Aspose.Slides para C++
description: Calcula hash do buffer.
type: docs
weight: 14
url: /pt/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) método

Calcula hash do buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer de origem. |

### Valor de Retorno

Valor de hash calculado.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) método

Calcula hash de um trecho do buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer de origem. |
| offset | int | Deslocamento no buffer de origem. |
| count | int | Número de bytes a usar do buffer de origem. |

### Valor de Retorno

Valor de hash calculado.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) método

Lê o fluxo até o final e calcula o hash dos dados lidos.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Fluxo de onde ler os dados. |

### Valor de Retorno

Valor de hash calculado para todos os dados do fluxo.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HashAlgorithm](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)