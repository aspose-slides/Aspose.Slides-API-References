---
title: AreSame()
second_title: Aspose.Slides para Referência da API C++
description: Are-same compara argumentos para a tradução da asserção AreSame.
type: docs
weight: 66
url: /pt/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) função

Are-same compara argumentos para a tradução da asserção AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS tipo de objeto. |
| T2 | RHS tipo de objeto. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expressão. |
| rhs_expr | const char * | RHS expressão. |
| lhs | const T1\& | LHS valor. |
| rhs | const T2\& | RHS valor. |

### Valor de Retorno

resultado da asserção em estilo gtest.

## Veja Também

* Espaço de nomes [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)