---
title: IsInstanceOf()
second_title: Aspose.Slides para C++ Referência da API
description: Is-instance-of-compara argumentos para a tradução da asserção IsInstanceOf.
type: docs
weight: 118
url: /pt/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) função


Is-instance-of-compara argumentos para a asserção IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do argumento. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | um objeto typeInfo que representa um tipo contra o qual o tipo de **obj** será comparado |
| obj | const T\& | Um objeto cujo tipo será comparado com o tipo especificado |

### Valor de Retorno

resultado de asserção estilo gtest.

## Veja Também

* Classe [TypeInfo](../../system/typeinfo/)
* Namespace [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)