---
title: EqualityComparerHashAdapter
second_title: Referência da API Aspose.Slides para C++
description: Adaptador para usar IEqualityComparer para hash. Usa o objeto comparador, se definido; caso contrário, usa o método de hash disponível selecionado usando a struct DictionaryHashSelector.
type: docs
weight: 677
url: /pt/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Adaptador para usar [IEqualityComparer](../iequalitycomparer/) para hash. Usa o objeto comparador, se definido; caso contrário, usa o método de hash disponível selecionado usando a struct [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Hashed | tipo. |
## Métodos

| Método | Descrição |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Cria adaptador sem comparador a ser usado. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Cria adaptador com o comparador fornecido a ser usado. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Calcula o valor de hash. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Define o comparador a ser usado. |

## Veja Também

* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)