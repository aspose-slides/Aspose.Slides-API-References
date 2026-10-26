---
title: begin()
second_title: Referência da API Aspose.Slides para C++
description: Acessador para o método begin() de uma coleção subjacente. Compila apenas se SmartPtr_ for tipo de especialização com o método begin().
type: docs
weight: 378
url: /pt/system/smartptr/begin/
---
## SmartPtr::begin() método


Acessador para [begin()](./) método de uma coleção subjacente. Compila apenas se SmartPtr_ for tipo de especialização com [begin()](./) método.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Valor de retorno

iterador para o início da coleção

## SmartPtr::begin() const método


Acessador para [begin()](./) método de uma coleção subjacente. Compila apenas se SmartPtr_ for tipo de especialização com [begin()](./) método.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Valor de retorno

iterador para o início da coleção

## Ver também

* Classe [SmartPtr](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)