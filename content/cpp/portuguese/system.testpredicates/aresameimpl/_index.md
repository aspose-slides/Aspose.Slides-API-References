---
title: AreSameImpl()
second_title: Referência da API Aspose.Slides para C++
description: Compara ponteiros inteligentes.
type: docs
weight: 79
url: /pt/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) função

Compara smart pointers.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T1 | Tipo de objeto do LHS. |
| T2 | Tipo de objeto do RHS. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expressão do LHS. |
| rhs_expr | const char * | Expressão do RHS. |
| lhs | const T1\& | Valor do LHS. |
| rhs | const T2\& | Valor do RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) função

Compara exceções.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T1 | Tipo de objeto do LHS. |
| T2 | Tipo de objeto do RHS. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expressão do LHS. |
| rhs_expr | const char * | Expressão do RHS. |
| lhs | const T1\& | Valor do LHS. |
| rhs | const T2\& | Valor do RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) função

Compara valores que não são ponteiros.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T1 | Tipo de objeto do LHS. |
| T2 | Tipo de objeto do RHS. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Expressão do LHS. |
| rhs_expr | const char * | Expressão do RHS. |
| lhs | const T1\& | Valor do LHS. |
| rhs | const T2\& | Valor do RHS. |

### Valor de retorno

Resultado de asserção no estilo gtest.

## Veja Também

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)