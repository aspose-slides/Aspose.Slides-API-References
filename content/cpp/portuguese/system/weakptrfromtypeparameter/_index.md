---
title: WeakPtrFromTypeParameter
second_title: Referência da API Aspose.Slides para C++
description: Estrutura de trait para converter o tipo de argumento em um ponteiro fraco, se for um tipo de ponteiro.
type: docs
weight: 2016
url: /pt/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

Estrutura de trait para converter o tipo de argumento em um ponteiro fraco, se for um tipo de ponteiro.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)