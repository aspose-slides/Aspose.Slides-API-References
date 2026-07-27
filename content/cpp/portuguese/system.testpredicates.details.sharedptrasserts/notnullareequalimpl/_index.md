---
title: NotNullAreEqualImpl()
second_title: Referência da API Aspose.Slides para C++
description: Compara igualdade entre arrays ou listas.
type: docs
weight: 40
url: /pt/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Compara igualdade entre arrays ou listas.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do contêiner LHS. |
| T2 | Tipo do contêiner RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que funciona como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado da asserção no estilo gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Compara igualdade entre instâncias de IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do elemento LHS. |
| T2 | Tipo do elemento RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que funciona como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado da asserção no estilo gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) function

Compara igualdade de tipos desconhecidos usando o método Equals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do objeto LHS. |
| T2 | Tipo do objeto RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |

### Valor de Retorno

resultado da asserção no estilo gtest.

## Veja Também

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)