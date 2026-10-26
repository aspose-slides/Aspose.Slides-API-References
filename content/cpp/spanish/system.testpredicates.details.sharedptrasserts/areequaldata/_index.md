---
title: AreEqualData()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Compara por igualdad dos contenedores usando System::Object::Equals en los elementos. Funciona con elementos SmartPtr."
type: docs
weight: 14
url: /es/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) función


Compara por igualdad dos contenedores usando [System::Object::Equals](../../system/object/equals/) en los elementos. Funciona con elementos [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T1 | Tipo de contenedor LHS. |
| T2 | Tipo de contenedor RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Referencia al contenedor LHS. |
| rhs | const T2\& | Referencia al contenedor RHS. |

### Return Value

Verdadero si los elementos contenidos y los tamaños coinciden, falso en caso contrario.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) función


Compara por igualdad dos contenedores usando operator == en los elementos. Funciona con elementos que no son SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T1 | Tipo de contenedor LHS. |
| T2 | Tipo de contenedor RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Contenedor LHS. |
| rhs | const T2\& | Contenedor RHS. |

### Return Value

Verdadero si los elementos contenidos y los tamaños coinciden, falso en caso contrario.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) función


Compara por igualdad dos contenedores del mismo tipo. Funciona con elementos que no son SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T1 | Tipo de contenedor LHS. |
| T2 | Tipo de contenedor RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T\& | Contenedor LHS. |
| rhs | const T\& | Contenedor RHS. |

### Return Value

Verdadero si los elementos contenidos y los tamaños coinciden, falso en caso contrario.

## Ver también

* Estructura [IsSmartPtr](../../system/issmartptr/)
* Espacio de nombres [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteca [Aspose.Slides](../../)