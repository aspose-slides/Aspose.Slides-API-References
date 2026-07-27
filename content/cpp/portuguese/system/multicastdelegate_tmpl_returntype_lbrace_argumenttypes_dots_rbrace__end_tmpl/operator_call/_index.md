---
title: operator()()
second_title: Referência da API Aspose.Slides para C++
description: Invoca todos os delegates atualmente presentes na coleção de delegates. Os delegates são invocados na mesma ordem em que foram adicionados à coleção. O operador bloqueia enquanto os delegates são executados.
type: docs
weight: 235
url: /pt/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const método

Invoca todos os delegates atualmente presentes na coleção de delegates. Os delegates são invocados na mesma ordem em que foram adicionados à coleção. O operador bloqueia enquanto os delegates são executados.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | ArgumentTypes... | Argumentos a serem passados para os delegates a serem invocados |

### Valor de Retorno

Valor de retorno do último delegate invocado

## Ver Também

* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)