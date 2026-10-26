---
title: Ref()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una referencia al objeto DynamicWeakPtr. Utilizado por el traductor al pasar argumentos de funciones por referencia.
type: docs
weight: 2458
url: /es/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) función

Crea una referencia al objeto [DynamicWeakPtr](../dynamicweakptr/). Utilizado por el traductor al pasar argumentos de funciones por referencia.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del puntero. |
| trunkMode | Modo del puntero inteligente en sí. |
| weakLeafs | Índices de los argumentos de plantilla para los que se debe llamar al método SetTemplateWeakPtr. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Puntero inteligente al que crear la referencia. |

### Valor devuelto

Referencia del puntero inteligente.

## System::Ref(T\&) función

Función auxiliar para obtener referencias a objetos. Se utiliza para garantizar que [System::DynamicWeakPtr](../dynamicweakptr/) actualiza el objeto referenciado después de las asignaciones.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que crear la referencia. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T\& | Valor al que crear la referencia. |

### Valor devuelto

Referencia al valor pasado a esta función.

## Ver también

* Clase [DynamicWeakPtr](../dynamicweakptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)