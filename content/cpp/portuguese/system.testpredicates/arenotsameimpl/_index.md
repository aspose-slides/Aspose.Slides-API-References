---
title: AreNotSameImpl()
second_title: Referência da API Aspose.Slides para C++
description: Are-not-same-compara ponteiros inteligentes.
type: docs
weight: 105
url: /pt/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) função


Are-not-same-compares ponteiros inteligentes.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de objeto LHS. |
| T2 | Tipo de objeto RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) função


Are-not-same-compares valores não ponteiro.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de objeto LHS. |
| T2 | Tipo de objeto RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |

### Valor de retorno

Resultado de asserção no estilo gtest.

## Veja também

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)