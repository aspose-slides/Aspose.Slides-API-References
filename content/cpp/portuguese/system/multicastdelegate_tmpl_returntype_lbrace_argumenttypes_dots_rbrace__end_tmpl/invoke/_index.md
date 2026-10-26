---
title: invoke()
second_title: Referência da API Aspose.Slides para C++
description: Invoca todos os delegates atualmente presentes na coleção de delegates. Delegates são invocados na mesma ordem em que foram adicionados à coleção. O método bloqueia enquanto os delegates são executados.
type: docs
weight: 222
url: /pt/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const método


Invoca todos os delegates atualmente presentes na coleção de delegates. Delegates são invocados na mesma ordem em que foram adicionados à coleção. O método bloqueia enquanto os delegates são executados.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | ArgumentTypes... | Argumentos a serem passados para os delegates a serem invocados |

### Valor de Retorno

Valor de retorno do último delegate invocado

## Veja Também

* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)