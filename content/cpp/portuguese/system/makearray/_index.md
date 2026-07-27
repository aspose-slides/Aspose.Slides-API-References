---
title: MakeArray()
second_title: Referência da API Aspose.Slides para C++
description: Uma função de fábrica que constrói um novo objeto Array, preenche-o com os elementos da lista de inicialização especificada e retorna um ponteiro inteligente que aponta para o objeto Array.
type: docs
weight: 2029
url: /pt/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) função


Uma função de fábrica que constrói um novo objeto [Array](../array/), preenche-o com os elementos da lista de inicialização especificada e retorna um ponteiro inteligente que aponta para o objeto [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do objeto [Array](../array/) que a função constrói |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| init | std::initializer_list\<T\> | A lista de inicialização contendo os elementos para preencher o array |

### Valor de retorno

Um ponteiro inteligente que aponta para o objeto [Array](../array/) construído

## System::MakeArray(Args\&&...) função


Uma função de fábrica que constrói um novo objeto [Array](../array/) passando os argumentos especificados ao seu construtor.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do objeto [Array](../array/) que a função constrói |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | Args\&&... | Os argumentos que são passados ao construtor do objeto [Array](../array/) que está sendo construído |

### Valor de retorno

Um ponteiro inteligente que aponta para o objeto [Array](../array/) construído

## System::MakeArray(Integral, Args\&&...) função


Uma função de fábrica que constrói um novo objeto [Array](../array/) passando os argumentos especificados ao seu construtor.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do objeto [Array](../array/) que a função constrói |
| Integral | Tipo do tamanho do array. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| size | Integral | Tamanho do array que está sendo criado. |
| args | Args\&&... | Os argumentos que são passados ao construtor do objeto [Array](../array/) que está sendo construído |

### Valor de retorno

Um ponteiro inteligente que aponta para o objeto [Array](../array/) construído

## Veja também

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)