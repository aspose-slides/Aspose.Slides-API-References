---
title: AreEqualData()
second_title: Aspose.Slides para C++ Referência da API
description: "Compara dois contêineres usando System::Object::Equals nos elementos. Funciona para elementos SmartPtr."
type: docs
weight: 14
url: /pt/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function


Compara dois contêineres usando [System::Object::Equals](../../system/object/equals/) nos elementos. Funciona para elementos [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | tipo de contêiner LHS. |
| T2 | tipo de contêiner RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs | const T1\& | referência ao contêiner LHS. |
| rhs | const T2\& | referência ao contêiner RHS. |

### Valor de retorno

True se os elementos contidos e os tamanhos coincidirem, false caso contrário.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function


Compara dois contêineres usando operator == nos elementos. Funciona para elementos que não são SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | tipo de contêiner LHS. |
| T2 | tipo de contêiner RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs | const T1\& | contêiner LHS. |
| rhs | const T2\& | contêiner RHS. |

### Valor de retorno

True se os elementos contidos e os tamanhos coincidirem, false caso contrário.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) function


Compara dois contêineres de tipo idêntico. Funciona para elementos que não são SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | tipo de contêiner LHS. |
| T2 | tipo de contêiner RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs | const T\& | contêiner LHS. |
| rhs | const T\& | contêiner RHS. |

### Valor de retorno

True se os elementos contidos e os tamanhos coincidirem, false caso contrário.

## Ver Também

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)