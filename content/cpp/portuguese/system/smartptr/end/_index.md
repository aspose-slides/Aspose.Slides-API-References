---
title: end()
second_title: Aspose.Slides para C++ Referência da API
description: Acessor para o método end() de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método end().
type: docs
weight: 391
url: /pt/system/smartptr/end/
---
## SmartPtr::end() método

Acessor para o método [end()](./) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### Valor de retorno

iterador para o final da coleção

## SmartPtr::end() const método

Acessor para o método [end()](./) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### Valor de retorno

iterador para o final da coleção

## Ver também

* Classe [SmartPtr](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)