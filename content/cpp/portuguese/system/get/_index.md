---
title: Get()
second_title: Referência da API Aspose.Slides para C++
description: Função para obter o N-ésimo elemento da tupla fornecida. Sobrecarga para objeto base.
type: docs
weight: 2406
url: /pt/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) função

Função para obter o N-ésimo elemento da tupla fornecida. Sobrecarga para objeto base.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| N | índice do elemento. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | objeto a ser inspecionado. |

### Valor de retorno

valor do N-ésimo elemento da tupla convertido para objeto.

## System::Get(const T\&) função

Função para obter o N-ésimo elemento da tupla fornecida. Sobrecarga para objetos com método Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| N | índice do elemento. |
| T | tipo do objeto inspecionado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | const T\& | objeto a ser inspecionado. |

### Valor de retorno

valor do N-ésimo elemento da tupla.

## System::Get(const SharedPtr\<T\>\&) função

Função para obter o N-ésimo elemento da tupla fornecida. Sobrecarga para ponteiros compartilhados.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| N | índice do elemento. |
| T | tipo do objeto inspecionado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | objeto a ser inspecionado. |

### Valor de retorno

valor do N-ésimo elemento da tupla.

## System::Get(T\&, const Index\&) função

Implementação para expressões collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo da coleção. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| collection | T\& | objeto da coleção. |
| index | const [Index](../index/)\& | índice do elemento do tipo [System.Index](../index/). |

### Valor de retorno

Elemento da coleção no deslocamento calculado.

## System::Get(T\&, const Range\&) função

Retorna uma fatia da coleção especificada definida pelo intervalo fornecido.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| collection | T\& | A coleção a ser fatiada. |
| range | const [Range](../range/)\& | O intervalo que especifica os limites da fatia. |

### Valor de retorno

Uma visualização ou fatia da coleção a partir do deslocamento inicial e do comprimento calculados.

## System::Get(const ValueTuple\<Args...\>\&) função

Obtém o N-ésimo elemento da tupla de valores.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| N | índice do elemento. |
| Args | elementos da tupla. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tupla da qual obter o elemento. |

### Valor de retorno

valor do N-ésimo elemento da tupla.

## Veja também

* Typedef [SharedPtr](../sharedptr/)
* Classe [Object](../object/)
* Classe [Index](../index/)
* Classe [Range](../range/)
* Classe [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)