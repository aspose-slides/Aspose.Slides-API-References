---
title: BlockCopy()
second_title: Referência da API Aspose.Slides para C++
description: Copia um número especificado de bytes do buffer de origem para o buffer de destino.
type: docs
weight: 1
url: /pt/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) método

Copia um número especificado de bytes do buffer de origem para o buffer de destino.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const **uint8_t** * | Ponteiro para o buffer de origem |
| srcOffset | int | Um deslocamento de byte no buffer de origem onde a cópia começa |
| dst | **uint8_t** * | Ponteiro para o buffer de destino |
| dstOffset | int | Um deslocamento de byte no buffer de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) método

Interpreta dois arrays tipados especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| TSrc | O tipo dos elementos do array de origem |
| TDst | O tipo dos elementos do array de destino |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | O array de origem |
| srcOffset | int | Um deslocamento de byte no array de origem onde a cópia começa |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | O array de destino |
| dstOffset | int | Um deslocamento de byte no array de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) método

Interpreta dois arrays especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | O array de origem |
| srcOffset | int | Um deslocamento de byte no array de origem onde a cópia começa |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | O array de destino |
| dstOffset | int | Um deslocamento de byte no array de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) método

Interpreta dois arrays tipados especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| TSrc | O tipo dos elementos da visualização do array de origem |
| TDst | O tipo dos elementos da visualização do array de destino |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | A visualização do array de origem |
| srcOffset | int | Um deslocamento de byte na visualização do array de origem onde a cópia começa |
| dst | const System::Details::ArrayView\<TDst\>\& | A visualização do array de destino |
| dstOffset | int | Um deslocamento de byte na visualização do array de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) método

Interpreta dois arrays tipados especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| TSrc | O tipo dos elementos do array de origem |
| TDst | O tipo dos elementos da visualização do array de destino |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | O array de origem |
| srcOffset | int | Um deslocamento de byte no array de origem onde a cópia começa |
| dst | const System::Details::ArrayView\<TDst\>\& | A visualização do array de destino |
| dstOffset | int | Um deslocamento de byte na visualização do array de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) método

Interpreta dois arrays tipados especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| TSrc | O tipo dos elementos da visualização do array de origem |
| TDst | O tipo dos elementos do array de destino |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | A visualização do array de origem |
| srcOffset | int | Um deslocamento de byte na visualização do array de origem onde a cópia começa |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | O array de destino |
| dstOffset | int | Um deslocamento de byte no array de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) método

Interpreta dois arrays tipados especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| TSrc | O tipo dos elementos do array de pilha de origem |
| NS | O tamanho do array de pilha de origem |
| TDst | O tipo dos elementos do array de pilha de destino |
| ND | O tamanho do array de pilha de destino |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | O array de pilha de origem |
| srcOffset | int | Um deslocamento de byte no array de pilha de origem onde a cópia começa |
| dst | const System::Details::StackArray\<TDst, ND\>\& | O array de pilha de destino |
| dstOffset | int | Um deslocamento de byte no array de pilha de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) método

Interpreta dois arrays tipados especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| TSrc | O tipo dos elementos do array de origem |
| TDst | O tipo dos elementos do array de pilha de destino |
| ND | O tamanho do array de pilha de destino |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | O array de origem |
| srcOffset | int | Um deslocamento de byte no array de origem onde a cópia começa |
| dst | const System::Details::StackArray\<TDst, ND\>\& | O array de pilha de destino |
| dstOffset | int | Um deslocamento de byte no array de pilha de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) método

Interpreta dois arrays tipados especificados como arrays brutos de bytes e copia os dados de um para o outro.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| TSrc | O tipo dos elementos do array de pilha de origem |
| NS | O tamanho do array de pilha de origem |
| TDst | O tipo dos elementos do array de destino |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | O array de pilha de origem |
| srcOffset | int | Um deslocamento de byte no array de pilha de origem onde a cópia começa |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | O array de destino |
| dstOffset | int | Um deslocamento de byte no array de destino onde a inserção de dados começa |
| count | int | O número de bytes a copiar |

## Ver também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Buffer](../)
* Classe [Array](../../array/)
* Classe [ArrayBase](../../arraybase/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)