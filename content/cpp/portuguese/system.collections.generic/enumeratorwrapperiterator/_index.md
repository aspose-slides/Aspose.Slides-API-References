---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides para Referência da API C++
description: Iterador que envolve o enumerador pré-criado e redireciona todas as chamadas para ele.
type: docs
weight: 196
url: /pt/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator classe


Iterador que envolve o enumerador pré-criado e redireciona todas as chamadas para ele.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| Element | Tipo de Element. |
## Métodos

| Método | Descrição |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Clona o iterador atual. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Avança o iterador em um passo. Deve atualizar m_is_end e m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Verifica se dois iteradores apontam para o mesmo item. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destrutor. |

## Ver também

* Namespace [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)