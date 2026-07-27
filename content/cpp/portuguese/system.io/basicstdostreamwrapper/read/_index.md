---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Se o modo de encapsulamento for binário, lê o número especificado de bytes do fluxo; caso contrário, lê o número especificado de caracteres e os converte para o tipo uint8_t. Grava o resultado da leitura no array de bytes especificado. Não suportado!
type: docs
weight: 66
url: /pt/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Se o modo de encapsulamento for binário, lê o número especificado de bytes do fluxo; caso contrário, lê o número especificado de caracteres e os converte para o tipo **uint8_t**. Grava o resultado da leitura no array de bytes especificado. Não suportado!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes onde gravar os bytes lidos |
| offset | **int32_t** | Uma posição baseada em 0 em **buffer** onde começar a gravar |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

Número de bytes ou caracteres lidos

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização do array de bytes onde gravar os bytes lidos |
| offset | **int32_t** | Uma posição baseada em 0 em **buffer** onde começar a gravar |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)