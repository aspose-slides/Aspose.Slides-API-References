---
title: MakeConstRef
second_title: Aspose.Slides para a Referência da API C++
description: Trait para criar um tipo genérico \"const reference\" se for String ou um tipo SmartPtr<>.
type: docs
weight: 1769
url: /pt/system/makeconstref/
---
## MakeConstRef struct
Trait para tornar o tipo genérico \"const reference\" se for [String](../string/) ou um tipo SmartPtr<>.
```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)