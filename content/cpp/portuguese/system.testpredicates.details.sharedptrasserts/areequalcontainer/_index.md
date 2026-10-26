---
title: AreEqualContainer()
second_title: Aspose.Slides para C++ Referência da API
description: Compara dois contêineres usando o operador == nos elementos. Funciona para elementos que não são SmartPtr.
type: docs
weight: 1
url: /pt/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) função


Compara dois contêineres usando o operador == nos elementos. Funciona para elementos que não são SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de contêiner LHS. |
| T2 | Tipo de contêiner RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs | const T1\& | Contêiner LHS. |
| rhs | const T2\& | Contêiner RHS. |

### Valor de retorno

Verdadeiro se os elementos contidos e os tamanhos coincidirem, falso caso contrário.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) função


Compara dois contêineres usando [System::Object::Equals](../../system/object/equals/) nos elementos. Funciona para elementos [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de contêiner LHS. |
| T2 | Tipo de contêiner RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs | const T1\& | Referência ao contêiner LHS. |
| rhs | const T2\& | Referência ao contêiner RHS. |

### Valor de retorno

Verdadeiro se os elementos contidos e os tamanhos coincidirem, falso caso contrário.

## Veja também

* Estrutura [IsSmartPtr](../../system/issmartptr/)
* Espaço de nomes [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteca [Aspose.Slides](../../)