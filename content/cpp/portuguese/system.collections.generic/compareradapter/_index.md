---
title: ComparerAdapter
second_title: Aspose.Slides para Referência da API C++
description: Adaptador para usar IComparer dentro do ambiente STL. Usa IComparer se definido; caso contrário, usa o operador < (se disponível) ou retorna false (se não).
type: docs
weight: 638
url: /pt/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adaptador para usar [IComparer](../icomparer/) dentro do ambiente STL. Usa [IComparer](../icomparer/) se definido; caso contrário, usa o operador < (se disponível) ou retorna false (se não).

```cpp
template<class T>class ComparerAdapter
```

### Template parameters

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo que está sendo comparado. |
## Methods

| Método | Descrição |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Constrói o adaptador sem nenhum comparador disponível. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Constrói o adaptador. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) função para tipos com operador < disponível. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) função para tipos sem operador < disponível. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Define o objeto comparador. |

## See Also

* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)