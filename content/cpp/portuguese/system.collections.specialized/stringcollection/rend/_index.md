---
title: rend()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um iterador reverso para o elemento que segue o último elemento do contêiner invertido. Corresponde ao elemento que precede o primeiro elemento do contêiner não invertido. Esse elemento funciona como um marcador de posição, tentar acessá-lo resulta em comportamento indefinido.
type: docs
weight: 287
url: /pt/system.collections.specialized/stringcollection/rend/
---
## StringCollection::rend() método

Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.

```cpp
reverse_iterator System::Collections::Specialized::StringCollection::rend() noexcept
```

### Valor de Retorno

An iterator pointing to the theoretical element preceding the first element of the container.

## StringCollection::rend() const método

Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.

```cpp
const_reverse_iterator System::Collections::Specialized::StringCollection::rend() const noexcept
```

### Valor de Retorno

An iterator pointing to the theoretical element preceding the first element of the const-qualified container.

## Veja Também

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* Classe [StringCollection](../)
* Namespace [System::Collections::Specialized](../../)
* Biblioteca [Aspose.Slides](../../../)