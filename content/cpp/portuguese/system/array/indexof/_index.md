---
title: IndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Determina o índice da primeira ocorrência do item especificado no array.
type: docs
weight: 131
url: /pt/system/array/indexof/
---
## Array::IndexOf(const T\&) const método

Determina o índice da primeira ocorrência do item especificado no array.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | const T\& | Índice do item a ser determinado |

### Valor de Retorno

[Index](../../index/) da primeira ocorrência do item especificado se o item for encontrado, caso contrário -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) método

Determina o índice da primeira ocorrência do item especificado no array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| ArrayType | Tipo de elementos no array de destino |
| ValueType | Tipo do item a ser pesquisado no array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para pesquisar o item especificado em |
| value | const [ValueType](../valuetype/)\& | Índice do item a ser determinado |

### Valor de Retorno

[Index](../../index/) da primeira ocorrência do item especificado se o item for encontrado, caso contrário -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) método

Determina o índice da primeira ocorrência do item especificado no array a partir do índice especificado.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| ArrayType | Tipo de elementos no array de destino |
| ValueType | Tipo do item a ser pesquisado no array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para pesquisar o item especificado em |
| value | const [ValueType](../valuetype/)\& | Índice do item a ser determinado |
| startIndex | int | [Index](../../index/) no qual a pesquisa é iniciada |

### Valor de Retorno

[Index](../../index/) da primeira ocorrência do item especificado se o item for encontrado, caso contrário -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) método

Determina o índice da primeira ocorrência do item especificado em um intervalo de itens do array definido pelo índice inicial e pelo número de elementos no intervalo.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| ArrayType | Tipo de elementos no array de destino |
| ValueType | Tipo do item a ser pesquisado no array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para pesquisar o item especificado em |
| value | const [ValueType](../valuetype/)\& | Índice do item a ser determinado |
| startIndex | int | [Index](../../index/) no qual a pesquisa é iniciada |
| count | int | Número de elementos do intervalo a ser pesquisado |

### Valor de Retorno

[Index](../../index/) da primeira ocorrência do item especificado se o item for encontrado, caso contrário -1

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)