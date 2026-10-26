---
title: ComparerType
second_title: Referência da API Aspose.Slides para C++
description: Compara elementos usando a semântica 'less'.
type: docs
weight: 144
url: /pt/system.collections.generic.details/comparertype/
---
## ComparerType struct

Compara elementos usando a semântica 'less'.

```cpp
template<typename T>class ComparerType
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo dos elementos comparados. |
## Métodos

| Método | Descrição |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compara tipos de valor que implementam a interface [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compara tipos de valor primitivos e objetos que não implementam a interface [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compara tipos de ponto flutuante. |

## Veja também

* Namespace [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)