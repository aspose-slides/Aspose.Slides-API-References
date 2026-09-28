---
title: AreEqualImpl()
second_title: Referência da API Aspose.Slides para C++
description: Compara igualdade de ponto flutuante com tipos aritméticos.
type: docs
weight: 27
url: /pt/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) função

Compara igualdade de ponto flutuante com tipos aritméticos.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
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
| lhs | const T1 | Valor LHS. |
| rhs | const T2 | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) função

Compara igualdade de valores, um ou ambos sendo [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) função

Compara igualdade de tipos não ponteiro usando o método Equals fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) função

Compara igualdade de tipos não ponteiro usando o método Equals fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) função

Compara igualdade de tipos não ponteiro usando o operador == fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) função

Compara igualdade de tipos boxable com valores [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T | Valor LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) função

Compara igualdade de tipos boxable com valores [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor LHS. |
| rhs | T | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) função

Compara igualdade de literal de string com valores [SmartPtr](../../system/smartptr/) usando desempacotamento.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const char16_t * | Valor LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) função

Compara igualdade de literal de string com valores [SmartPtr](../../system/smartptr/) usando desempacotamento.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor LHS. |
| rhs | const char16_t * | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) função

Compara igualdade de tipo aleatório com nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T | Valor LHS. |
| s | std::nullptr_t | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) função

Compara igualdade de tipo aleatório com nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| rhs | std::nullptr_t | Valor RHS. |
| s | T | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) função

Compara igualdade de tipos ponteiro.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parâmetros de modelo

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

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) função

Compara igualdade de tipos ponteiro.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parâmetros de modelo

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

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) função

Compara igualdade de um tipo aleatório com um valor [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```


### Parâmetros de modelo

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
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) função

Compara igualdade de um valor [Nullable](../../system/nullable/) com um tipo aleatório.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo LHS. |
| T2 | Tipo RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Valor LHS. |
| rhs | T2 | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) função

Compara igualdade de tipos aleatórios usando algoritmos gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Parâmetros de modelo

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

resultado de asserção estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) função

Compara igualdade de dois valores [System::String](../../system/string/), protegendo contra a invocação de uma função membro em um [String](../../system/string/) nulo. Templatizada (em vez de uma sobrecarga simples que recebe const [String](../../system/string/)&) para que chamadas de tipos mistos – por exemplo, um literal de string char16_t comparado a um [String](../../system/string/) – falhem ao deduzir um único T consistente e sejam excluídas deste candidato completamente, em vez de competir com o modelo genérico AreEqualImpl<T1,T2> via o parâmetro seletor long long/int e produzir uma resolução de sobrecarga ambígua.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Object](../../system/object/), restrito a [System::String](../../system/string/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Um parâmetro de serviço que serve como seletor da implementação da função; o valor do parâmetro é ignorado |

### Valor de Retorno

resultado de asserção estilo gtest.

## Veja Também

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [String](../../system/string/)
* Classe [Object](../../system/object/)
* Classe [Stream](../../system.io/stream/)
* Classe [Nullable](../../system/nullable/)
* Estrutura [IsSmartPtr](../../system/issmartptr/)
* Estrutura [IsBoxable](../../system/isboxable/)
* Estrutura [IsStringByteSequence](../../system/isstringbytesequence/)
* Estrutura [IsNullable](../../system/isnullable/)
* Espaço de nomes [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)