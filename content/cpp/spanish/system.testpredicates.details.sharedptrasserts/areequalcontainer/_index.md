---
title: AreEqualContainer()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara dos contenedores usando el operador == en los elementos. Funciona con elementos que no son SmartPtr.
type: docs
weight: 1
url: /es/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) función

Compara dos contenedores usando el operador == en los elementos. Funciona con elementos que no son SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo de contenedor del lado izquierdo. |
| T2 | Tipo de contenedor del lado derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | const T1\& | Contenedor del lado izquierdo. |
| rhs | const T2\& | Contenedor del lado derecho. |

### Valor de retorno

true si los elementos contenidos y los tamaños coinciden, false en caso contrario.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) función

Compara dos contenedores usando [System::Object::Equals](../../system/object/equals/) en los elementos. Funciona con elementos [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo de contenedor del lado izquierdo. |
| T2 | Tipo de contenedor del lado derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | const T1\& | Referencia al contenedor del lado izquierdo. |
| rhs | const T2\& | Referencia al contenedor del lado derecho. |

### Valor de retorno

true si los elementos contenidos y los tamaños coinciden, false en caso contrario.

## Véase también

* Struct [IsSmartPtr](../../system/issmartptr/)
* Espacio de nombres [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)