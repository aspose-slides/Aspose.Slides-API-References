---
title: LastIndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Determina o índice da última ocorrência do item especificado em um intervalo de itens do array especificado pelo índice inicial e pelo número de elementos no intervalo.
type: docs
weight: 703
url: /pt/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Determina o índice da última ocorrência do item especificado em um intervalo de itens do array especificado pelo índice inicial e pelo número de elementos no intervalo.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ArrayType | Tipo dos elementos no array alvo |
| ValueType | tipo do item a ser buscado no array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar o item especificado |
| value | const [ValueType](../valuetype/)\& | Índice do item a ser determinado |
| startIndex | int | [Index](../../index/) onde a busca é iniciada |
| count | int | Número de elementos do intervalo onde pesquisar |

### Valor de Retorno

[Index](../../index/) da última ocorrência do item especificado se o item for encontrado, caso contrário -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Determina o índice da última ocorrência do item especificado no array a partir do índice especificado.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ArrayType | Tipo dos elementos no array alvo |
| ValueType | tipo do item a ser buscado no array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar o item especificado |
| value | const [ValueType](../valuetype/)\& | Índice do item a ser determinado |
| startIndex | int | [Index](../../index/) onde a busca é iniciada |

### Valor de Retorno

[Index](../../index/) da última ocorrência do item especificado se o item for encontrado, caso contrário -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Determina o índice da última ocorrência do item especificado no array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ArrayType | Tipo dos elementos no array alvo |
| ValueType | tipo do item a ser buscado no array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar o item especificado |
| value | const [ValueType](../valuetype/)\& | Índice do item a ser determinado |

### Valor de Retorno

[Index](../../index/) da última ocorrência do item especificado se o item for encontrado, caso contrário -1

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Classe [Array](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)