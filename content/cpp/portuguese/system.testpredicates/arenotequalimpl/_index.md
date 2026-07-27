---
title: AreNotEqualImpl()
second_title: Referência da API Aspose.Slides para C++
description: Compara valores que não são iguais quando um ou ambos são Decimal.
type: docs
weight: 53
url: /pt/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Não-igual compara valores, um ou ambos sendo [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de Modelo

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
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Não-igual compara tipos não ponteiro usando o método Equals fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Não-igual compara tipos não ponteiro usando o método Equals fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Não-igual compara tipos não ponteiro usando o operador != fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Não-igual compara tipos empacotáveis com valores [SmartPtr](../../system/smartptr/) usando desempacotamento.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T | Valor LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Não-igual compara tipos empacotáveis com valores [SmartPtr](../../system/smartptr/) usando desempacotamento.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor LHS. |
| rhs | T | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Não-igual compara tipo aleatório com nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T | Valor LHS. |
| s | std::nullptr_t | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Não-igual compara tipo aleatório com nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| rhs | std::nullptr_t | Valor RHS. |
| s | T | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Comparação de igualdade para tipos ponteiro.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo LHS. |
| T2 | Tipo RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function

Compara igualdade de tipos aleatórios usando algoritmos gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo LHS. |
| T2 | Tipo RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T1 | Valor LHS. |
| rhs | T2 | Valor RHS. |

### Valor de Retorno

Resultado de asserção no estilo gtest.

## Veja Também

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [Object](../../system/object/)
* Estrutura [IsSmartPtr](../../system/issmartptr/)
* Estrutura [IsBoxable](../../system/isboxable/)
* Espaço de nomes [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)