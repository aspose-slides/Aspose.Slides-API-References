---
title: MemoryStream()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe MemoryStream com capacidade inicial igual a 0.
type: docs
weight: 1
url: /pt/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() construtor


Constrói uma nova instância da classe [MemoryStream](../) com capacidade inicial igual a 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) construtor


Constrói uma nova instância da classe [MemoryStream](../) que representa um fluxo baseado em um buffer de memória do tamanho especificado.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity_ | int | O tamanho em bytes de um buffer de memória associado ao fluxo representado pelo objeto que está sendo criado |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) construtor


Constrói uma nova instância da classe [MemoryStream](../) que representa um fluxo de memória conectado ao buffer de memória especificado. Um parâmetro indica se o fluxo é writable.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Um array de bytes a ser usado como buffer de memória no qual o fluxo representado pelo objeto que está sendo criado será baseado |
| writable | **bool** | Especifica se o fluxo deve ser writable |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) construtor


Constrói uma nova instância da classe [MemoryStream](../) que representa um fluxo de memória conectado a um segmento do buffer de memória especificado, iniciando no índice especificado e incluindo o número especificado de elementos. Os parâmetros especificam se o fluxo é writable e se o método GetBytes() pode ser chamado.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Um array de bytes cujo segmento será usado como buffer de memória no qual o fluxo representado pelo objeto que está sendo criado será baseado |
| index | int | Um índice baseado em zero do elemento em **content** onde o segmento começa |
| count | int | O número de elementos de **content** incluídos no segmento |
| writable | **bool** | Especifica se o fluxo deve ser writable |
| publiclyVisible | **bool** | Especifica se o buffer de memória subjacente deve ser disponibilizado ao chamador do método GetByte() |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [MemoryStream](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)