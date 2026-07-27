---
title: cbegin()
second_title: Referência de API Aspose.Slides para C++
description: Acessador para o método cbegin() de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método cbegin().
type: docs
weight: 404
url: /pt/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const método

Acessor para o método [cbegin()](./) de uma coleção subjacente. Compila somente se SmartPtr_ for um tipo de especialização com o método [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Valor de Retorno

iterador para o início da coleção

## Veja Também

* Classe [SmartPtr](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)