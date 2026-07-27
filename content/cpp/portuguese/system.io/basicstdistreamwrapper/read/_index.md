---
title: Read()
second_title: Referência da API Aspose.Slides for C++
description: Se o modo de encapsulamento for binário, lê o número especificado de bytes do fluxo, caso contrário lê o número especificado de caracteres e os converte para o tipo uint8_t. Escreve o resultado da leitura no array de bytes especificado.
type: docs
weight: 66
url: /pt/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Se o modo de encapsulamento for binário, lê o número especificado de bytes do fluxo, caso contrário lê o número especificado de caracteres e os converte para o tipo **uint8_t**. Escreve o resultado da leitura no array de bytes especificado.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes onde escrever os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde começar a escrever |
| count | **int32_t** | O número de bytes a ler |

### Valor de retorno

Número de bytes ou caracteres lidos

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lê o número especificado de bytes do fluxo e os escreve no array de bytes especificado.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array de bytes onde escrever os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde começar a escrever |
| count | **int32_t** | O número de bytes a ler |

### Valor de retorno

O número de bytes lidos

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)