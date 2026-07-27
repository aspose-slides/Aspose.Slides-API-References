---
title: NotNullAreNotEqualImpl()
second_title: Referência da API Aspose.Slides para C++
description: Compara desigualdade de arrays ou listas.
type: docs
weight: 105
url: /pt/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) função

Compara desigualdade de arrays ou listas.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de contêiner LHS. |
| T2 | Tipo de contêiner RHS. |

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

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) função

Compara desigualdade de instâncias IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de elemento LHS. |
| T2 | Tipo de elemento RHS. |

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

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) função

Compara desigualdade de tipos desconhecidos usando o método Eqauals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Parâmetros do modelo

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

## Ver também

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Espaço de nomes [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)