---
title: GetValue()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el valor de la propiedad de un objeto específico.
type: docs
weight: 1
url: /es/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) método


Obtiene el valor de la propiedad de un objeto específico.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) para leer la propiedad de. |

### Valor devuelto

Valor de la propiedad especificada para el objeto especificado.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) método


Obtiene el valor de la propiedad de un objeto específico.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) para leer la propiedad de. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Estos son valores de índice opcionales para propiedades indexadas. Para propiedades no indexadas, este valor debe ser nulo. |

### Valor devuelto

Valor de la propiedad especificada para el objeto especificado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)